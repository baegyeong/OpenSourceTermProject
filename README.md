YOLO, opencv, Pytorch 오픈소스를 이용한 쓰레기 종류 분석 프로젝트입니다.

사용한 오픈소스는 다음과 같습니다.
* colab: 구글에서 제공하는 클라우드 기반 주피터 노트북으로, 주로 yolo는 코랩에서 작업(cuda를 대체할 gpu환경을 제공하기 때문)
* YOLOv5, pytorch: 깃허브에서 다운받은 라벨링 gui를 사용하여 이미지 라벨링 후, yolov5와 pytorch를 사용하여 모델 학습 (훈련 수: 200)
* opencv: 쓰레기들을 웹캠을 통해 실시간으로 분석하기 위해 opencv를 사용
