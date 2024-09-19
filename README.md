# Tennis Game Analyzer

This project focuses on analyzing tennis matches by tracking player and ball movement, measuring player speed and ball shot speed. It uses YOLO for detecting players and the tennis ball in real-time and Convolutional Neural Networks (CNNs) to extract court key-points.

## Features

- Player and Ball Detection: Real-time detection of players and the tennis ball using YOLO.
- Court Key-point Extraction: Extracts tennis court key-points using CNNs.
- Player and Ball Tracking: Tracks player movement and calculates ball speed.
- Performance Analytics: Measures player speed and ball shot speed.

## Technologies Used

- YOLO (You Only Look Once): Object detection model for real-time player and ball tracking.
- CNNs (Convolutional Neural Networks): Used for court key-point extraction.
- OpenCV: For video processing and visualizations.
- Python: Main programming language for model implementation.
- PyTorch: (Specify which) used for building and training the CNN models.

## Models Used

* YOLO v8 for player detection
* Fine Tuned YOLO for tennis ball detection
* Court Key point extraction

* Trained YOLOV5 model: https://drive.google.com/file/d/1UZwiG1jkWgce9lNhxJ2L0NVjX1vGM05U/view?usp=sharing
* Trained tennis court key point model: https://drive.google.com/file/d/1QrTOF1ToQ4plsSZbkBs3zOLkVt3MBlta/view?usp=sharing


## Installation

1. Clone the repository:
```bash
   git clone https://github.com/Kaushalvadadoria28/Tennis-Game-Analysis.git
   cd Tennis-Game-Analysis
```

2. Install the required dependencies: Make sure you have Python 3.x installed. Install dependencies with:
```bash
   pip install -r requirements.txt
```

3. Download YOLO weights: Download the YOLO pre-trained weights from the official website or other sources and place them in the weights/ folder.

4. Set up the environment:

    - Ensure OpenCV, YOLO, and CNN models are properly set up and configured in your environment.
      
5. Training

      * Tennis ball detetcor with YOLO: training/tennis_ball_detector_training.ipynb
      * Tennis court keypoint with Pytorch: training/tennis_court_keypoints_training.ipynb

## Output Videos

Here is a screenshot from one of the output videos:

![Screenshot (418)](https://github.com/user-attachments/assets/a816650f-ce16-42cf-8eb8-d4e0f9856401)
  
## Future Enhancements

- Adding real-time match statistics and player performance summaries.
- Improving ball trajectory tracking for more accurate shot speed calculation.
- Enhancing the user interface with a dashboard for better visualization.

## Contributing

Contributions are welcome! If you have ideas for improvements, new features, or bug fixes, feel free to submit issues or pull requests.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.
