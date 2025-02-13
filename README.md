# PharmaMatcher-GUI:Medicine Recommender System
A simple Drugs matching system.

MedRecSys is a simple and intuitive medicine recommendation system. This project leverages natural language processing (NLP) and machine learning techniques to provide similar medicine recommendations based on user input. The system is complemented with a graphical user interface (GUI) built using Tkinter.

## Features

- **Medicine Data Processing**: Uses pandas and numpy for data manipulation.
- **Text Processing**: Applies NLP techniques such as stemming and vectorization.
- **Similarity Calculation**: Utilizes cosine similarity to find and recommend similar medicines.
- **User Interface**: Provides an easy-to-use GUI for entering medicine names and viewing recommendations.

## Getting Started

Project Structure

PharmaMatcher/<br>
├── medicine.csv             # Dataset file<br>
├── app.py                   # Main application file<br>
├── medicine_dict.pkl        # Pickled dictionary of processed medicine data<br>
├── similarity.pkl           # Pickled similarity matrix<br>
└── README.md                # Project README file<br>

