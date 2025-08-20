This is a repository for an inference API using yolov5.
It is supported on Linux, windows, and Mac os.

#Prerequisites
OS: any
Python 3.7+
FastAPI pip install fastapi
ASGI Server pip install uvicorn

#Check For Prerequisites
FastAPI: pip show fastapi
uvicorn: pip show uvicorn

#Endpoints Summary
/Train-Model (POST)
Accepts all required parameters as user input and returns a successfully trained message at the end.

https://github.com/user-attachments/assets/40723c75-5083-4932-9d0a-c0ed6a0dbe7a

/Show-Inference (POST)
Performs inference on an image using the specified model and returns the bounding boxes of the class in an image/png format.

![Inference](https://github.com/user-attachments/assets/875aebb5-3fab-453f-9c1d-4105ab7de955)

#Model Structure

The folder yolov5_api contains a file for the code
The Structure of yolov5_api folder is as follows:
│──models
  │──yolov5_api
  │  │──api.py
  │  │──tempCodeRunnerFile.python
  │  │──yolov5s.pt
  │
  │──__pycache__
  │  │──api.cpython-313.pyc

  <img width="775" height="141" alt="image" src="https://github.com/user-attachments/assets/1da9d17d-c899-45b2-9c39-8bae823c27af" />

