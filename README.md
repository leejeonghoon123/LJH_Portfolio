기업 프로젝트 (선도 소프트)


작업기간 : 2023.05.17~ 2023.06.08 


조원: 조경민, 김명현, 김시아, 이건화, 이상미, 이정훈, 임동빈, 정주희 (총 8명)

파이썬 크롤링을 이용한 전자정부 프레임 워크 지리정보 표시 웹 사이트

------------------------------------------------------------------------------------------------------------------------

    내가 만든 파트

파이썬 크롤링부분
    
    
![파이썬 크롤링 1](https://github.com/leejeonghoon123/LJH_Portfolio/assets/127282120/c73e60e7-4d29-4268-900e-db0019276c9d)
pj1.py 코드를 통해 한국 보호지역 통합DB SHP파일을 다운로드 하게 작성하였다.

        
pj4.py 코드를 통해 관측지점별 실시간 어장정보를 xml로 받아오는 코드를 작성하였다.

![파이썬 크롤링 2](https://github.com/leejeonghoon123/LJH_Portfolio/assets/127282120/9250d4e1-6bb2-406f-bf51-84ddcf252b8e)

pj4.py 파일의 경우 실시간 정보이기 떄문에 작업스케줄러 설정을 통해 매일 10분간격으로 실행되어 DB에 저장되도록 하였다.

지오서버 레이어 발행


![지오서버 레이어1](https://github.com/leejeonghoon123/LJH_Portfolio/assets/127282120/8990b610-1fd8-495d-b795-735aedd1df77)
![지오서버 레이어2](https://github.com/leejeonghoon123/LJH_Portfolio/assets/127282120/00097360-a453-4ad1-8fb4-7211ce0f9f29)
저장된 DB를 조인하여 해당 지역 정보들을 가지고 있는 레이어를 발행하였다.



