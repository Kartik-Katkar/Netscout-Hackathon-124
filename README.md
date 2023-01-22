# Netscout-Hackathon-124

# Apk Download link - [Click here](https://drive.google.com/file/d/1RcuqHLubaNoYvyt9j2iR_wl-fbsfn_sy/view?usp=sharing)

- Project: Leaf Disease Detection App using Flutter.
- Description : A Flutter app that detects a plant's disease given a photo of an affected part of the plant.
- Youtube Video Link: [click here](https://youtu.be/YlkDWJhiR54)
- The application was built using Flutter and a tflite model from Teachable Machine Learning by Google. The dataset was from KAGGLE.

## Visuals
<img src="https://user-images.githubusercontent.com/102908142/213900031-76131c4c-fae9-4211-a381-c2abff3dc76f.jpeg" height="500">


## Installation
A Flutter installation is required to run this project.
You can also download the apk instead 
To install Flutter, visit the official installation [documentation](https://docs.flutter.dev/get-started/install).
Set up an editor of choice as specified [here](https://docs.flutter.dev/get-started/editor).

Download the project.

```bash
git clone https://github.com/Kartik-Katkar/Netscout-Hackathon-124.git
```

Run the below command inside the project directory to install necessary packages.
```bash
flutter pub get
```
To run the project in debug mode 
```bash
flutter run
```

To generate a release build
```bash
flutter build apk
```
Locate the `app-release.apk` file from the directory `build/app/outputs/flutter-apk/` and install in your Android smartphone or emulator to use.

## Important to note
- The `tflite` model has been trained to detect only a subset of the diseases. They include:
    - Pepper Bell Bacterial Spot
    - Pepper Bell Healthy
    - Potato Early Blight
    - Potato Healthy
    - Potato Late Blight
    - Tomato Bacterial Spot
    - Tomato Early Blight
    - Tomato Healthy
    - Tomato Late Blight
    - Tomato Leaf Mold
    - Tomato Septoria Leaf Spot
    - Tomato Spotted Spider Mites
    - Tomato Target Spot
    - Tomato Mosaic Virus
    - Tomato Yellow Leaf Curl Virus

- The size of the dataset was only sufficient enough to make the model recognize selected  diseases, but it faces problems with images of non-plants.
- The application was built using Flutter and a `tflite` model from [Teachable Machine Learning by Google](https://teachablemachine.withgoogle.com/). The dataset was from [KAGGLE](https://www.kaggle.com/saroz014/plant-diseases).
