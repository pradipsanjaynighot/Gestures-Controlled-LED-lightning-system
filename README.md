
install python 3.10.0 version after downloading check in cmd python --version
pip install opencv-python
pip install mediapipe
pip install pyserial
if cv2 error do: 
1) pip show opencv-python
python -c "import sys; print(sys.executable)"
pip uninstall opencv-python
python -m pip install opencv-python --no-user

again if problem continues run as administrator cmd
python -m pip install opencv-python
python -c "import cv2"


and then run the program firstproject.py in vs code 
Command to run:python firstproject.py 

