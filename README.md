기업 프로젝트 (선도 소프트)


작업기간 : 2023.05.17~ 2023.06.08 


조원: 조경민, 김명현, 김시아, 이건화, 이상미, 이정훈, 임동빈, 정주희 (총 8명)

파이썬 크롤링을 이용한 전자정부 프레임 워크 지리정보 표시 웹 사이트

------------------------------------------------------------------------------------------------------------------------

    내가 만든 파트
------------------------------------------------------------------------------------------------------------------------

    파이썬 크롤링
    
    
![파이썬 크롤링 1](https://github.com/leejeonghoon123/LJH_Portfolio/assets/127282120/c73e60e7-4d29-4268-900e-db0019276c9d)

![파이썬 크롤링 2](https://github.com/leejeonghoon123/LJH_Portfolio/assets/127282120/9250d4e1-6bb2-406f-bf51-84ddcf252b8e)


pj1.py 코드를 통해 한국 보호지역 통합DB SHP파일을 다운로드 하게 작성하였다.
        
pj4.py 코드를 통해 관측지점별 실시간 어장정보를 xml로 받아오는 코드를 작성하였다.

pj4.py 파일의 경우 실시간 정보이기 떄문에 작업스케줄러 설정을 통해 매일 10분간격으로 실행되어 DB에 저장되도록 하였다.

------------------------------------------------------------------------------------------------------------------------

    지오서버 레이어 발행


![지오서버 레이어1](https://github.com/leejeonghoon123/LJH_Portfolio/assets/127282120/8990b610-1fd8-495d-b795-735aedd1df77)

![지오서버 레이어2](https://github.com/leejeonghoon123/LJH_Portfolio/assets/127282120/00097360-a453-4ad1-8fb4-7211ce0f9f29)


저장된 DB를 조인하여 해당 지역 정보들을 가지고 있는 레이어를 발행하였다.

이런 방식으로 모든 DB정보들과 QGIS 레이어들을 지오서버 레이어로 발행하였다.

![지오서버 레이어3](https://github.com/leejeonghoon123/LJH_Portfolio/assets/127282120/26e5c353-8fd6-4a94-908c-5c90da50f391)

------------------------------------------------------------------------------------------------------------------------

    자바 개발
    
------------------------------------------------------------------------------------------------------------------------
    
    검색파트
    

![화면1](https://github.com/leejeonghoon123/LJH_Portfolio/assets/127282120/44d5d280-92a0-4a13-b666-462c8b5c2775)

![화면2](https://github.com/leejeonghoon123/LJH_Portfolio/assets/127282120/012c5056-3658-426b-abcb-a99abbbd4d05)

![화면3](https://github.com/leejeonghoon123/LJH_Portfolio/assets/127282120/db5d2aee-57be-425c-9d81-37658e221213)

![화면4](https://github.com/leejeonghoon123/LJH_Portfolio/assets/127282120/a90329f0-7a84-4054-9326-5ed7114bbce2)

![검색1](https://github.com/leejeonghoon123/LJH_Portfolio/assets/127282120/2f2a1210-4b65-4324-91a7-b604c09acbf4)

위의 화면처럼 기본 창에서 왼쪽 상단의 검색창에 검색어를 입력할 경우, 리스트 중에 검색어와 일치하는 항목들만 나타나도록 search.js에서 코드를 작성하였다.

------------------------------------------------------------------------------------------------------------------------
    
    지오서버에서 발행한 레이어 스크립트로 가져오기


![지오서버 레이어 가져오기1](https://github.com/leejeonghoon123/LJH_Portfolio/assets/127282120/73be1a02-cf9a-4bd2-9cd8-b4dad7d49225)

![지오서버 레이어 가져오기2](https://github.com/leejeonghoon123/LJH_Portfolio/assets/127282120/f7a44eee-f0a8-4ab8-9f7e-9c66e7702d84)

![지오서버 레이어 가져오기3](https://github.com/leejeonghoon123/LJH_Portfolio/assets/127282120/f043e194-fada-4878-a4e8-16515881b2c5)

이처럼 체크박스 클릭 시, 해당하는 정보들이 화면상에 나타나도록 레이어들을 지오서버에서 불러와 나타내는 기능을 작성하였다.

![지오서버 레이어 가져오기4](https://github.com/leejeonghoon123/LJH_Portfolio/assets/127282120/a0bbb1cc-7604-41ac-aad1-0efca1bedbdc)

------------------------------------------------------------------------------------------------------------------------
    
    WFS 파일로 받아와서 이미지 변경



![WFS 2](https://github.com/leejeonghoon123/LJH_Portfolio/assets/127282120/386f0899-5057-4b80-960a-a0c0438f5ec3)


![WFS 1](https://github.com/leejeonghoon123/LJH_Portfolio/assets/127282120/559df7ec-77d8-4789-9c61-85d7c657ef60)

레이어만 가져오게되면 해당하는 지역의 데이터들을 알 수 없기때문에 WFS 파일로 가져와서 해당하는 레이어의 이미지도 바꾸어주었다.

------------------------------------------------------------------------------------------------------------------------
    
    마우스 오버시 해당하는 지역의 정보 팝업창 생성
    
![팝업창1](https://github.com/leejeonghoon123/LJH_Portfolio/assets/127282120/61ea58e0-615b-4dc6-ac6e-ccc13e8448f0)

![팝업창2](https://github.com/leejeonghoon123/LJH_Portfolio/assets/127282120/9166e1ac-ce2f-4e26-9ffe-82f1fc785c05)

![팝업창3](https://github.com/leejeonghoon123/LJH_Portfolio/assets/127282120/18571f0f-bb7b-4fa3-8b87-0fe8cebfe25d)

![팝업창4](https://github.com/leejeonghoon123/LJH_Portfolio/assets/127282120/e56c3a9c-2195-4727-b3c2-7ce6457cefa1)

마우스 오버하는 레이어의 해당하는 정보들을 나타낼 수 있게 layer.js에 코드를 작성하였고, 팝업창 또한 main.jsp에 만들어 두었다.

모든 레이어에서 마우스 오버 시 팝업창이 나타나지 않도록 레이어 필터를 통해 해당하는 레이어를 지정해주었고, 오버레이또한 각각 설정해 주었다.

