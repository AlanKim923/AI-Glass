AI Glass입니다.

메인 실행 코드 파일은 face_recognition_demo.py 파일입니다.

안면인식장애를 가지고 있는 사람들을 위해서 만들게 되었습니다.

INTEL의 openvino를 사용하였습니다.

웹캠으로 받아온 이미지를 인공지능 모델로 얼굴을 인식합니다.

얼굴의 두 눈, 코, 입 양쪽 총 5개의 점을 찍어 얼굴을 인식합니다.

얼굴을 인식하여 등록이 되어있는 사람이라면 '~~님이 앞에 있습니다.' 라고 음성으로 알려주게 됩니다.

등록이 되어있지 않은 사람이라면 '모르는 사람이 앞에 있습니다.' 라고 음성으로 알려줍니다.

이때 음성은 Google의 tts를 사용하였습니다.