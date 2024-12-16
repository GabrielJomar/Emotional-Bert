

Detects emotions in text (anger, disgust, fear, joy, sadness, surprise, neutral) using a pre-trained transformer model.
Maps complex emotions to core Ekman emotions for simplified analysis.
Response Generation

Generates empathetic responses tailored to the detected emotion using a GPT-2-based model.
Focuses on making users feel understood and supported.
Workflow
Data Preprocessing

Cleans and tokenizes text data.
Maps complex emotions to simplified labels using an Ekman emotion mapping JSON.
Model Training

Fine-tunes the pre-trained emotion classifier (michellejieli/emotion_text_classifier) on the processed dataset.
Saves and reloads the fine-tuned model for inference.
Emotion Prediction

Predicts emotions for new input text using the fine-tuned model.
Prompt Engineering and Response Generation

Generates a prompt with context about the user’s emotion.
Uses a GPT-2-based model to create empathetic and constructive responses.

