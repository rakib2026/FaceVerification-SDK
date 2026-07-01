# FaceVerification-SDK

A lightweight Python FaceOnLive SDK for face verification, ID verification, and face liveness detection.

---

## Overview

This project provides a simple Python SDK to integrate face verification and identity verification features into applications.

It can be used for face matching, ID verification, and liveness detection in basic biometric workflows.

---

## About

This SDK is built for simple face verification, ID verification, and face liveness detection use cases. It provides a basic Python interface for integrating biometric features into applications.

Powered by **[FaceOnLive](https://faceonlive.com/)** technology.


```

## Features

- Face Verification
- ID Verification
- Face Liveness Detection
- Face Matching


```

install from source:

```bash
git clone https://github.com/<your-username>/FaceVerification-SDK.git
cd FaceVerification-SDK
pip install -r requirements.txt
```

---

## Usage

```python
from faceverification_sdk import Client

client = Client(api_key="YOUR_API_KEY")
```

### Face Verification

```python
result = client.verify_face(
    image_1="image1.jpg",
    image_2="image2.jpg"
)

print(result)
```

### ID Verification

```python
result = client.verify_id(
    id_image="id.jpg",
    face_image="selfie.jpg"
)

print(result)
```

---

## About

This SDK is based on FaceOnLive.

https://faceonlive.com/

---

## License

MIT
