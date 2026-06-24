# Wine Classification Using KNN

A stylish browser-based machine learning project that classifies wine samples using the K-Nearest Neighbors (KNN) algorithm implemented from scratch in JavaScript.

This project uses the classic Wine dataset and includes:
- A custom KNN model.
- A wine-themed UI.
- Interactive input fields for manual classification.
- Visual outputs such as neighbor votes, a confusion matrix, and feature plots.

## Features

- KNN classification built from scratch in vanilla JavaScript.
- Wine dataset with 13 numeric features and 3 classes.
- Automatic train/test split.
- Accuracy and F1-score calculation.
- Confusion matrix display.
- Interactive classification form with preset samples.
- Wine-inspired UI with subtle animation and floating particles.

## Dataset

This project uses the classic Wine dataset, which contains:
- 178 samples
- 13 numeric features
- 3 classes

The dataset is commonly used for beginner machine learning classification tasks.

## How It Works

1. The dataset is split into training and test sets.
2. Features are standardized before distance calculation.
3. The KNN algorithm finds the nearest neighbors for a sample.
4. The class with the most votes is returned as the prediction.

## How to Run

1. Download or clone the repository.
2. Open the `index.html` file in your browser.
3. Enter wine measurements manually or use one of the preset buttons.
4. Click **Classify Wine** to see the result.

## File Structure

```bash
project-folder/
├── index.html
└── README.md
```

## Technologies Used

- HTML5
- CSS3
- Vanilla JavaScript

## Notes

- The project runs fully in the browser.
- No external backend or build tools are required.
- The UI is designed to be simple, elegant, and easy to present in a classroom or portfolio setting.

## License

This project is for educational use.
