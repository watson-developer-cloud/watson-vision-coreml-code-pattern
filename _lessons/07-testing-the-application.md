---
title: Testing the application
---

1. You can run the application in the simulator or on a device. To run in the simulator, choose a phone option from the dropdown and click run
2. To run on a device you need to add a developer account. Do this by going to the ‘Signing’ section of the project settings. Open the dropdown for ‘Team.’ Click ‘Add Account.’ If you have an apple developer account you can sign into that. If you do not, you can click ‘Create Apple ID’ to create one. Plug your iPhone into the laptop and select that as your device in the dropdown in the upper left corner of Xcode
3. Click the ‘run’ button
4. Once the app is downloaded to your device you can begin taking pictures by clicking the camera icon in the upper left. If you are using the simulator, you can add photos to it by dragging them into the simulator
5. The application will use the Watson Visual Recognition Core ML model to classify the cables. It will then send that classification label to Discovery to get relevant information about it