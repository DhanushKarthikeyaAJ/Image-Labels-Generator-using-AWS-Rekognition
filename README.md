# 🖼️ Image Labels Generator using Amazon Rekognition

This project uses AWS Rekognition to automatically detect and return labels from uploaded images in S3 using a serverless Lambda function.

## 📌 Features
- Auto-labeling of images using Rekognition.
- Triggered on S3 uploads.
- Fully serverless using AWS Lambda and IAM.
- Easy to extend to APIs or frontends.

## 🛠️ Tech Stack
- AWS S3
- AWS Rekognition
- AWS Lambda (Python)
- IAM Roles

## 📷 Example Output
```json
[
  {
    "Name": "Dog",
    "Confidence": 99.7
  },
  {
    "Name": "Pet",
    "Confidence": 96.3
  }
]
