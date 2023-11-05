![Screenshot (357)](https://github.com/shrinathasati/Drishti-The-boon-for-blind/assets/120880974/61f6ef33-429c-4651-8d1e-cf2b0c271b9c)
# Drishti-The-boon-for-blind
Drishti is the name of a machine learning model which detects any objects and provides the voice feedback for user. It's aim to provide the artificial vision for blind. I have used many libraires of python and trained with large number of objects named as yolo_coco.
We have provide an external interface for that using flask. This model provide output as string and we can convert this output string to voice using google-text-to-speech(gtts) library.
# Instruction to use:
there are two main source codes files:-
1. realtimeaudio.py
2. app.py

(i) using realtime audio we can also use this model but in internal environment
(ii) to provide the abstraction layer we have made the app.py file where we have used flask.

# Development tools:-
1. VS Code
2. ffmpeg

# Libraries used:-
1. Flask
2. Numpy
3. Pydub
4. Subprocess
5. gtts
6. os
