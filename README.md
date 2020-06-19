#На основе facenet-face-recognition


(из facenet-face-recognition readme) This repository contains a demonstration of face recognition using the FaceNet network (https://arxiv.org/pdf/1503.03832.pdf) and a webcam. Our implementation feeds frames from the webcam to the network to determine whether or not the frame contains an individual we recognize.

## How to use

To install all the requirements for the project run

	pip install -r requirements.txt

Это Flask-приложение, так что, чтобы запустить его из консоли, наберите 

	export FLASK_APP=start.py
	python -m flask run

Либо настройте соответствующие параметры запуска в среде разработки (например pycharm)