# Height_Measuring_Device


초음파 센서 2개를 활용해서 adult인지, child 인지 판단합니다.

이걸 ROS 통신으로 보내려고 라즈베리파이 하나를 장착했고 라즈베리파이 sd 카드 안쪽에도 door.py 파일이 있어요.
라즈베리파이 연결된 상태로 rosrun 라즈베리파이 안쪽에 있는 파일명 door.py 실행 가능합니다.

rostopic list로 sensor1, sensor2, height 값 확인 가능. 



낮은 위치에 있는 초음파 센서에 사람이 근접하면 어린이,
높은 위치에 있는 초음파 센서에 사람이 근접하면 어른이다라고 인지하는 매커니즘. 

