# FNAF-CV
ACM AI Project Winter '26

2/6/26 DEMO
Ran in venv with python 3.12 (python 3.13+ doesnt have pytorch support)
numpy==1.26.4
opencv-python==4.10.0.84

trained with downscaled hagrid dataset
https://huggingface.co/datasets/cj-mills/hagrid-sample-500k-384p

detects palm, stop, stop_inverted, fist

to run demo in virtual environment:

python3.12 -m venv venv

source venv/bin/activate

pip install --upgrade pip

pip install numpy==1.26.4

pip install torch torchvision torchaudio

pip install opencv-python==4.10.0.84

pip install mediapipe pillow

python webcam_gesture_demo.py
