# Speech-Recognition-using-HuggingFace-Transformers

Here’s a summary of the steps I followed to extract text from audio using the Wav2Vec 2.0 model:

1. Install Required Libraries: Installed the transformers and librosa libraries to work with audio and pre-trained models.

2. Import Libraries: Imported necessary libraries such as librosa for audio processing and transformers for using the Wav2Vec model.

3.Load the Pre-trained Model and Tokenizer: Loaded the Wav2Vec 2.0 model and tokenizer from Hugging Face, which are pre-trained for automatic speech recognition.

4. Load the Audio File: Loaded the chosen audio file into the notebook using librosa and using IPython display to play the audio file for a quick check.

5. Tokenize the Audio Input: Tokenized the audio data to convert it into a format suitable for the model.

6. Get Model Predictions: Fed the tokenized input into the model to get logits, which are the raw predictions from the model.

7. Extract Predicted IDs: Used the argmax function to identify the most likely predicted tokens from the logits.

8. Decode Predictions to Text: Decoded the predicted IDs back into human-readable text.

Finally, I printed the extracted text from the audio.

This workflow allows to effectively transcribe speech from audio files using advanced machine learning techniques.
