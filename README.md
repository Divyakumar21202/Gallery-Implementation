# Gallery Image Fetching App

This Android application allows users to select an image from their device's gallery and display it in an ImageView. 
It demonstrates how to use the `Intent.ACTION_PICK` action to open the device's gallery and retrieve selected images.

## Usage

1. Clone this repository to your local machine using the following command:

2. Open the project in Android Studio.

3. Build and run the app on an Android emulator or physical device.

4. Click the "Fetch Image" button to open the device's gallery and select an image.

5. The selected image will be displayed in the ImageView.

## Code Overview

The code in this repository provides a simple example of image fetching using Android's MediaStore.

- The `MainActivity` class sets up the UI and handles the image fetching process.
- The `GALLERY_REQUEST_CODE` is used to identify the gallery image request.
- When the "Fetch Image" button is clicked, the app opens the gallery using an intent.
- The selected image is displayed in the `ImageView` using `setImageURI`.

## Author

- [DivyaKumar Patel](https://github.com/Divyakumar21202)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
