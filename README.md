# Streaming Video with FastAPI

You will need to place some `video.mp4` or modify the video path in the source code.

How to run
```
poetry install && poetry shell
uvicorn main:app --reload
```

This implementation run the server and load the video in 1MB chunks so would not overwhelmed the user with bandwith and storage.