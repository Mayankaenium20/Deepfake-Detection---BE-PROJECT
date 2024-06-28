# Deepfake Detection System

## Overview
This project implements a deepfake detection system using PyTorch for training the detection model and Django for the web application interface. The system allows users to upload videos, which are then analyzed to determine if they contain deepfake content.

## Features
- **Deepfake Detection**: Uses a convolutional neural network (CNN) to detect deepfake videos.
- **User-Friendly Interface**: Django-based web application for easy video upload and analysis.
- **High Accuracy**: Achieves high accuracy in detecting manipulated videos.
- **Real-Time Analysis**: Provides immediate feedback on the authenticity of uploaded videos.

## Technologies Used
- **PyTorch**: For building and training the deepfake detection model.
- **Django**: For creating the web application and handling HTTP requests.
- **Python**: Primary programming language for the project.
- **HTML/CSS**: For the web interface (handled by Django templates).

## Installation

1. **Clone the repository**:
    ```sh
    git clone https://github.com/yourusername/deepfake-detection-system.git
    cd deepfake-detection-system
    ```
2. **Upload the models**:
     ```sh
    i. Create a folder named 'models' under the Django Application folder.
   ii. Download and add the saved models from the following link into that folder.
    ```

2. **Create a virtual environment**:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the dependencies**:
    ```sh
    pip install -r requirements.txt
    ```

4. **Run the migrations**:
    ```sh
    python manage.py migrate
    ```

5. **Start the Django development server**:
    ```sh
    python manage.py runserver
    ```

6. **Access the application**:
    Open your web browser and go to `http://127.0.0.1:8000`.

## Usage
1. **Upload a video**: Navigate to the upload page and select a video file.
2. **Analyze the video**: Click the "Upload" button to start the analysis.
3. **View results**: The system will display whether the video is a deepfake or not.

## Project Structure
- `manage.py`: Command-line utility for administrative tasks.
- `settings.py`: Configuration settings for the Django project.
- `urls.py`: URL routing for the web application.
- `apps.py`: Configuration for the Django app.
- `models.py`: Defines the database models (if used).
- `views.py`: Contains the logic for handling HTTP requests and rendering HTML.
- `templates/`: Directory for HTML templates.
- `static/`: Directory for static files (CSS, JavaScript).

## Contributing
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature-name`).
3. Commit your changes (`git commit -am 'Add some feature'`).
4. Push to the branch (`git push origin feature/your-feature-name`).
5. Create a new Pull Request.

## Contributors
1. Yash Nande
2. Siddhant Misal
3. Mayuresh Chowugule
   
## License
This project is licensed under the MIT License.
