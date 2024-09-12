# AI Quiz Developer Overview

This document outlines the features and functionalities of the Quiz App, designed to generate quizzes based on user inputs and uploaded content.

## Features

- **Quiz Generation**: Users can create quizzes by uploading PDF files, selecting subjects, or entering specific topics.
  
- **Customization Options**:
  - **Number of Questions**: Users can specify how many questions they want in the quiz (1 to 10).
  - **Type of Quiz**: Options include Multiple-Choice and True-False.
  - **Difficulty Level**: Users can choose from Easy, Medium, or Hard.
  - **Language**: Available languages include English, Urdu, and French.

## Functionality

1. **Upload Content**: Users can upload a PDF file, and the app will extract text to generate quiz questions based on the content.
  
2. **Select Subject**: For quizzes related to Data Science, users can choose from main subjects like Machine Learning, Deep Learning, Mathematics, and Statistics, along with specific sub-fields.

3. **Dynamic Question Generation**: The app utilizes a generative AI model to create unique quiz questions, ensuring that no previously asked questions are repeated.

4. **User Interaction**:
   - Users can answer quiz questions and receive immediate feedback on their performance.
   - The app displays correct answers and explanations for better understanding.

## Technical Details

- **Technologies Used**:
  - **Streamlit**: For building the web application interface.
  - **PyPDF2**: For extracting text from PDF files.
  - **Generative AI Model**: To create quiz questions based on user-defined parameters.

## Conclusion

The Quiz App is designed to facilitate learning through interactive quizzes, allowing users to engage with various subjects and topics effectively. By utilizing advanced AI technologies, it provides a seamless experience in quiz generation and assessment.

