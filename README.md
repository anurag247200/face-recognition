# Real-Time Face Recognition and Monitoring System
This project implements a real-time face recognition and monitoring system using Python, OpenCV, and Jupyter Notebook. The system is designed to detect and recognize faces from a live video feed (e.g., webcam) and display the name of the recognized individuals. The face recognition model is trained using the Local Binary Patterns Histograms (LBPH) algorithm, which is effective for face recognition tasks.


## Dataset Preparation
Create a dataset folder in the root directory of the project.
Inside the dataset folder, create a separate subfolder for each person you want to recognize. The subfolder’s name should be the name of the person (e.g., person1, person2).
Place multiple images of each person inside their respective subfolders. The images should clearly show the person’s face, and they can be in any common image format like .jpg or .png.

Running the Program
1. Clone the repository and navigate to the project directory.
2. Ensure your dataset is correctly structured as described above.
3. Run the script to start the real-time face recognition:   "python main.py"
4. Press 'q' to stop the live feed and close the camera.

## Notes
Make sure all images in the dataset are of the same dimensions (e.g., 100x100 pixels). The script automatically resizes images if needed.
For better accuracy, ensure that the images used for training are of high quality and clearly depict the individual's face. You can run this project on any IDE that supports Python, such as PyCharm, VS Code, or Jupyter Notebook.

## Contributing
Contributions are welcome! Feel free to fork the repository, make your changes, and submit a pull request.
