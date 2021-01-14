# EmotionAI

EmotionAI is a face detection application that uses artificial intelligence and face recognition determines the user's emotions through their webcam in real time.

Visit the deployed site here: https://emotionai.vercel.app/

<p>
<img src="https://i.imgur.com/P8Jjryo.png" width="100" alt="emotionai_neutral">
<img src="https://i.imgur.com/pMF5fmx.png" width="100" alt="emotionai_happy">
<img src="https://i.imgur.com/42u2B3f.png" width="100" alt="emotionai_surprised">
</p>

## Getting Started

Once the site loads, a popup should appear asking for access to your webcam (there may be a slight delay due to facecam loading speeds);

<p align="center"><img src="https://i.imgur.com/8yLBUDZ.png" alt="webcam_ask"></p>

Look directly at your camera and start making some facial expressions!

The program will first search the webcam screen for your face using its face landmark detection. It then displays its certainty of the higlighted object being a human face in decimal form above your face.

Lastly, it will detect what emotion you are feeling (happy, sad, surprised, etc.) relative to your facial features and display its certainty in its assumptionin decimal form below your face.

## Acknowledgements

- face-api.js library ( https://github.com/justadudewhohacks/face-api.js ), wrapper around TensorFlow (machine-learning library).
