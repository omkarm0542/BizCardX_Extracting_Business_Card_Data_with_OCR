# BizCardX: Extracting Business Card Data with OCR
![Screenshot 2023-06-23 152602](https://github.com/omkarm0542/BizCardX_Extracting_Business_Card_Data_with_OCR/assets/123791884/f0b8f1c3-4edd-493e-834d-87663b611e0f)


BizCardX is a Python application that utilizes Optical Character Recognition (OCR) technology to extract data from business cards. It provides a user-friendly Graphical User Interface (GUI) built with Streamlit and stores the extracted data in an SQL database. This repository contains all the necessary code and instructions to set up and use BizCardX effectively.

## Features
* Extracts key information from business cards, including name, phone number, email address, and company name.
* Supports various business card formats and layouts.
* Provides a clean and intuitive GUI for easy interaction.
* Stores extracted data in an SQL database for further analysis and processing.

  ![Screenshot 2023-06-23 152617](https://github.com/omkarm0542/BizCardX_Extracting_Business_Card_Data_with_OCR/assets/123791884/84ce3150-fd55-460a-9916-27620240899a)

## Technologies Used
BizCardX leverages the following technologies:

* OCR:  Utilizes OCR technology to recognize and extract text from business card images. This is implemented using the Tesseract OCR library.
* Streamlit GUI: Employs Streamlit, a powerful Python library, to create a user-friendly and interactive GUI for the application.
* SQL Database: Stores the extracted business card data in an SQL database, allowing for efficient data management and retrieval.
* Data Extraction: Implements algorithms and techniques for accurately extracting relevant information from business card images.
## Installation
Follow these steps to install and set up BizCardX on your local machine:

1. Clone this GitHub repository:

```
git clone https://github.com/your-username/bizcardx.git
```

2. Navigate to the project directory:

```
cd bizcardx
```

3. Run the application:


```
streamlit run app.py
```

4. ### Open your web browser and visit http://localhost:8501 to access the BizCardX GUI.

## Usage
1. Launch the BizCardX application by following the installation instructions.

2. Click on the "Upload Image" button in the GUI to upload a business card image in a common image format (e.g., JPEG, PNG).

3. After uploading, the application will process the image using OCR and display the extracted data on the screen.

4. The extracted data will also be stored in the SQL database for future reference and analysis.

5. Use the search and filter functionalities provided in the GUI to retrieve and view specific business card data from the database.

## Acknowledgements
BizCardX acknowledges the following open-source projects for their valuable contributions:

1. Streamlit: The Streamlit development team for creating an amazing GUI framework.
2. Easy OCR: The easy OCR community for providing an excellent OCR engine.
3. MYSQL connector
### Contact
For any inquiries or feedback, please contact the project maintainer at omkarm0542@gmail.com.

### here is the example of business cards 
![1](https://github.com/omkarm0542/BizCardX_Extracting_Business_Card_Data_with_OCR/assets/123791884/21083c42-ee5a-462f-aae4-ae5b2dc99b62)

![5](https://github.com/omkarm0542/BizCardX_Extracting_Business_Card_Data_with_OCR/assets/123791884/e33ae8c6-f5d5-40dc-b7d9-9c06771e9852)
