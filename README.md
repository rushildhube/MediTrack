# MediTrack
MediTrack is a patient medical record management system designed to efficiently record, store, and share patient data, including medical reports, X-rays, diagnoses, treatments, medications, blood test results, and more. This application provides a comprehensive solution for tracking and managing patient information securely.

## Features

- **Patient Data Management**:
  - Record and store patient information, including name, age, gender, diagnosis, treatment, and medication details.

- **Document Upload**:
  - Upload and store medical documents such as X-rays, blood reports, and patient records securely within the application.

- **Blood Test Results Upload**:
  - Upload blood test results and save them into an Excel file for detailed analysis and record-keeping.

- **Date and Time Tracking**:
  - Automatically track the date and time of each patient record entry for accurate timestamping.

- **Email Integration**:
  - Share patient details and uploaded data via email with doctors for consultation and collaboration.

## Technologies Used

- **Python**: Backend programming language for application logic and data processing.
- **Firebase**: Cloud-based platform for authentication, real-time database, and file storage.
- **Firestore**: NoSQL cloud database for storing patient records and related data.
- **smtplib (from Python)**: Library for sending emails directly from Python applications.

## Python Libraries Used

- **tkinter**: GUI toolkit for creating graphical user interfaces in Python applications.
- **kivy**: Open-source Python library for developing multi-touch applications.
- **pandas**: Data manipulation library for data analysis and handling tabular data.
- **firebase-admin**: Firebase Admin SDK for Python to interact with Firebase services programmatically.
- **openpyxl**: Library for reading and writing Excel files in Python applications.

## Installation and Setup

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/rushildhube/MediTrack.git
   ```

2. **Install Dependencies**:
   ```bash
   cd MediTrack
   pip install -r requirements.txt
   ```

3. **Run the Application**:
   ```bash
   python main.py
   ```

## Contributing

We welcome contributions to enhance the functionality and features of the MediTrack project. If you wish to contribute, please follow these guidelines:

- Fork the repository to your GitHub account.
- Create a new branch for your feature or bug fix.
- Make your changes and ensure all tests pass.
- Commit your changes with descriptive messages.
- Push your changes to your branch.
- Open a pull request to merge your changes into the main repository.

## License

This project is licensed under the MIT License. For more details, refer to the [LICENSE](LICENSE.txt) file.

---

Feel free to further customize the README file to include specific details, guidelines, or additional sections based on the requirements and scope of the "MediTrack" project.
