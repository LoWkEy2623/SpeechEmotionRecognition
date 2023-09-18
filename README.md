# [How to Make a Speech Emotion Recognizer Using Python And Scikit-learn](https://www.thepythoncode.com/article/building-a-speech-emotion-recognizer-using-sklearn)
To run this, you need to:
- `pip3 install -r requirements.txt`

It is already trained, you can use `test.py` to test your voice.

You can:
- Tweak the model parameters ( or the whole model ) in `ser.py`.
- Add more data to `data` folder in condition that the audio samples are converted to 16000Hz sample rate and mono channel, `convert_wavs.py` does that.
- Editing the emotions specified in `utils.py` in `AVAILABLE_EMOTIONS` constant.

When you modified anything, you can run `ser.py` to retrain the model.
Add as much of dataset as possible to make it accurate.Datasets can be downloaded from https://www.kaggle.com.
