---
title: Configuring the application
date: 2018-01-09
---

# THIS PAGE NEEDS UPDATED

1. Open the project directory in finder. You can do this with the following command
```bash
open .
```
Then double click the `Core ML Vision.xcodeproj` file to open the project in Xcode
![](assets/xcode_open_project.png)
1. Open the file called `CameraViewController.swift`
![](assets/xcode_open_file.png)
1. Go back to the Visual Recognition dashboard, where you trained your model
![](assets/visual_recognition_dashboard.png)
1. Click the **Credentials** tab
![](assets/visual_recognition_credentials_page.png)
1. Click **View Credentials**. We'll need to copy the `api_key`
![](assets/visual_recognition_view_credentials.png)
1. Paste the `api_key` into the `ImageClassificationViewController.swift` file, at the line that reads
```swift
let visualRecognitionApiKey = ""
```
1. Navigate back to the Visual Recognition dashboard once again, scroll down to the section labeled **Custom Models**
![](assets/visual_recognition_get_model_id.png)
1. Click **Copy model ID**
1. Paste the **Model ID** into the `ImageClassificationViewController.swift` file, at the line that reads
```Swift
let visualRecognitionClassifierID = ""
```
