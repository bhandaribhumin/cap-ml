# Image Reader

Sample Ionic+Angular App that uses 'cap-ml' plugin to detect text in images

## Install Prerequisites

This is an Ionic Project, so install ionic globally like this -
`npm install -g @ionic/cli`

## Running the App

- Checkout the repository at https://github.com/bendyworks/cap-ml
- Navigate to examples/text-detection/ImageReader
- Install dependencies - `npm install`
- Build the project - `npm run build` or `ionic build`
- Open the project
  - ios app
    - Open the app in XCode using `npx cap open ios`
    - run the app either on a simulator or device.

  - Android app -
    - open the app in Android Studio `npx cap open android`
    - Run the app either on a simulator or device.

- Once the app opens up, click on 'Pick a Picture' and select a picture with some text.
- App will immediately process the image and present text detections on the image chosen.
- Click on the highlighted regions to get the text in that location.

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/bendyworks/cap-ml.

## License
Hippocratic License Version 2.0.

For more information, refer to LICENSE file
