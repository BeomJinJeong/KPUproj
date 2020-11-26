# Emergency Situation Recognition System Using CCTV and Deep Learning

CCTV와 딥러닝을 이용한 응급 상황 인식 시스템입니다.
Google Colaboratory 서버를 사용하고 있으며 해당 서버와 로컬 서버의 연결이 필요하며
USB 포트를 사용하는 웹캠/CCTV/Camera가 연결되어 있어야 합니다.

# Ready

1. 로컬 서버에 tensorflow-gpu v1.13.1 과 cuda v10.0.1 이 설치되어있어야 합니다. 
2. https://research.google.com/colaboratory/local-runtimes.html 문서를 통해 Colab과 로컬 런타임을 연결합니다.
3. 'cuda10_0_tensorflow_gpu_1_13_1.ipynb'의 내용 중, Model-Web_local threading 목차의 쉘에서 "MRCNN_pure_02"라고 되어있는 기본 폴더의 이름을 이 git에서 다운받은 폴더명으로 재지정해줍니다.
4. Model-Web-threading 목차의 쉘을 실행하고, 결과에 나온 URL을 실행합니다.
