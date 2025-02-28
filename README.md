# Real-Time Body Segmentation Web App

This project demonstrates a real-time body segmentation web application built using TensorFlow.js and React.js. It utilizes the pre-trained BodyPix model to identify and segment body parts from live webcam video, displaying the results in a dynamic web interface.

## Introduction

This application showcases the power of client-side machine learning for real-time computer vision tasks. By leveraging TensorFlow.js and the BodyPix model, we can perform body segmentation directly in the browser without relying on server-side processing. This project is a great starting point for anyone interested in exploring real-time computer vision applications in web development.

## Installation

1.  **Clone the repository:**

    ```bash
    git clone [https://github.com/sonivaibhav-git/CV-BodySegmentation.git](https://github.com/sonivaibhav-git/CV-BodySegmentation.git)
    cd CV-BodySegmentation
    ```

2.  **Install dependencies:**

    ```bash
    npm install
    ```

## Run Process

1.  **Start the development server:**

    ```bash
    npm run dev
    ```

2.  **Open the application in your browser:**

    The application will be accessible at `http://localhost:5173`.

3.  **Allow webcam access:**

    Your browser will prompt you to grant access to your webcam. Allow access for the application to function correctly.

4.  **Observe the real-time body segmentation:**

    You should now see a live feed from your webcam with body parts segmented and highlighted.

## Dependencies

- React.js
- TensorFlow.js (@tensorflow/tfjs)
- BodyPix (@tensorflow-models/body-pix)

## Further Development

This project can be extended to include:

- Different segmentation effects (e.g., blurring the background, replacing the background).
- Integration with other web APIs.
- Improved performance optimization.

Feel free to contribute and enhance this project!
