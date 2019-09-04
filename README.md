# wayou 와유
 1908  
 suggests a new way of enjoying and treasuring an image 이미지를 색다른 방식으로 유람하고 간직하도록.  
   
   
 와유란, '누워서 유람하다'라는 뜻으로, 과거에 명승과 고적이 그려진 그림을 오래도록 바라보며 여행을 하는 듯이 즐김을 비유적으로 이르는 말이다.  
 현대인 역시 흡사한 방식으로 세상을 유람한다.  
 차이는 한 장도 갖기 어려웠던 과거에 비해, 현재는 사진의 등장으로 이미지가 되려 범람한다는 것이다.  
 한 장의 이미지를 보다 더 각별하게 즐겼으면 하는 바람에서 시작된 '와유'는 이미지에게 되려 휘발성을 지니게끔 한다.  
 랜덤으로 크롤링한 이미지를 보여줌으로써 이미지의 출처와 경로를 숨겼고, 한 번 감상을 남기고 나면 이미지는 영영 사라진다.  
 어떤 이미지를 보고 남겼을지 모를 단상만이 차곡차곡 쌓인다. 
 
  
![wy2](https://user-images.githubusercontent.com/54440974/64242199-15ac9800-cf40-11e9-9371-78cb635b9411.gif)  
  
위의 버튼을 누르면 이미지가 등장한다.  
이미지는 미리 입력해둔 여행 관련 인스타 해시태그들 중 하나가 랜덤으로 골라져, 해당 해시태그의 인기 게시물 중 하나를 크롤링해 가져온다.  
selenium을 사용했다.   
  
    
![wy3](https://user-images.githubusercontent.com/54440974/64242262-31b03980-cf40-11e9-8cb1-6e2b32ab7093.gif)  
  
카메라 버튼을 누르면 '찰칵' 알림과 함께, 이미지는 사라지고 단상은 오른쪽에 쌓인다.
  
    
![wy4](https://user-images.githubusercontent.com/54440974/64242350-51476200-cf40-11e9-8311-d5100e9e8784.gif)  
  
쌓여있는 단상들.  
  
    
![wy5](https://user-images.githubusercontent.com/54440974/64242385-5dcbba80-cf40-11e9-94db-64d649ee4a10.gif)  
  
gif 상의 단상들은 이미지를 보고 임의로 남겨놓은 감상들이지만, 추후에는 소박하게나마 배포할 예정.
사람들이 어떤 감정들을 남길지 기대된다.
다만 크롤링 특성 상 로딩 시간이 길어질 때가 있어, 로딩 화면을 따로 만들어야 할 필요가 있어 보인다. 
