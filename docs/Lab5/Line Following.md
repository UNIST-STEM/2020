# Line Following

 이번 주 마지막 도전을 위해, 여러분은 바닥에 놓인 컬러 테이프를 따라 코스의 결승선에 오르기 위해 경주용 자동차를 프로그래밍해야 할 것이다. 당신의 차는 두 가지 일을 해야 한다.

 1. 자신이 선택한 색상 선과 다른 색상 선을 다르게 인식
 2. 컬러 테이프에 의존에서 목표 지점까지 도달

 우선 우리가 작성해야 하는 함수는 두개이다.
 두 함수 모두 `line Follow.py` 파일 안에 있는 함수다.

 `size_calc()` 함수와 `drive_car_callback()` 함수를 작성해야 한다.

 두 함수를 작성하기 위해서는 `color_segmentation.py` 에 있는 `cd_color_segmentation()` 함수를 이해해야 하는데 이 함수의 역할은 여러분이 앞선 강좌인 `Color Segmentation` 에서 설정한 HSV 필터를 통해 인식된 특정 색의 물체를 박스로 표시해주는 역할을 하는 함수이다. 이 함수의 return 값은 표시된 박스의 각 모서리 좌표값이다. 
  

`이 링크` 에 들어가면
 color_segmentation 및 driveNode의 빈 복사본에 대한 링크가 여기에 있다. color_segmentation에서 IMAGE_TOPIC("/zze_node/color_seg_output") 항목으로 이미지를 게시하도록 드라이브Node 및 color_segation이 수정되었다. 이전에 사용했던 것과 동일한 명령어를 사용하여 도커에 로그인하되, 피쉬버그/레이스카 다음에 스페이스와 자동차 번호를 추가하십시오. 그런 다음 도커에서 rqt_image_view를 열고 color_seg_output 항목을 선택하여 color_seg 필터 후 zed 카메라 피드를 볼 수 있다. "연결 유효하지 않은" 오류가 발생하면 무시하십시오. 어쨌든 작동하는 경향이 있습니다.
  
 추가한 출판사 것 말고도, 이것들은 기본적으로 빈 파일들이야. 네가 원하는 대로 마음대로 가지고 다니렴.