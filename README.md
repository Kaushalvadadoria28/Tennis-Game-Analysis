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

## Future Enhancements

- Adding real-time match statistics and player performance summaries.
- Improving ball trajectory tracking for more accurate shot speed calculation.
- Enhancing the user interface with a dashboard for better visualization.

## Contributing

Contributions are welcome! If you have ideas for improvements, new features, or bug fixes, feel free to submit issues or pull requests.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.
