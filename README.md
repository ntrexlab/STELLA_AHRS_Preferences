# STELLA_AHRS_Preferences
STELLA 구동 시 AHRS 센서 값 이상한 경우 윈도우 환경에서 UI를 통해 설정 값을 확인하셔야 됩니다.


***
## 1. 사용 하드웨어 및 Tool
 * #### 사용 하드웨어 
    - AHRS - [MW_AHRSv1](http://www.devicemart.co.kr/goods/view?no=1310790)
     - USB2RS232_ahrscable - [USB2RS232_ahrscable](http://www.devicemart.co.kr/goods/view?no=1310790)
     - USB2RS232 구매경로 - [USB2RS232_USB2RS232(https://smartstore.naver.com/phonepong/products/7222108269)
* #### 사용 Tool
    - AHRS_UI -> [다운로드 경로](https://github.com/ntrexlab/MW_AHRS_Manual/blob/main/AHRS_UI.exe)</br>

     
***
## **환경 설정 확인 방법**
***
#### 1. AHRS를 USB2RS232&AhrsCable 제품을 이용하여 연결합니다. 
![ahrs_5_1](https://user-images.githubusercontent.com/85467544/155052035-bff76b37-f0bd-4b38-b17c-d09c7100c35a.png)
 위에 사진을 보고 연결하시면 됩니다.
#### 2. 연결한 제품을 PC에 연결합니다.
![ahrs_6](https://user-images.githubusercontent.com/85467544/155052044-3a1f01d8-2ccf-4688-a4bd-b19d8de88d3c.jpg)
#### 3. AHRS UI를 실행한 후 Connect 버튼을 클릭합니다.
![ahrs_1](https://user-images.githubusercontent.com/85467544/155051990-a971622a-71f1-435d-8c67-2c0a11d3c987.png)
#### 4. 컴퓨터에 잡혀있는 포트 번호를 확인 후에 COM Port와 Baudrate을 설정합니다. 그리고 Connect 버튼 클릭합니다. 
![ahrs_2](https://user-images.githubusercontent.com/85467544/155051997-8b42113a-a596-460a-8056-ae420b9261a6.png)
#### 5. Temperature(1) 나오면 정상 연결된 것입니다. 이후 Configure 버튼 클릭합니다.
![ahrs_3](https://user-images.githubusercontent.com/85467544/155052002-d1b7f123-00bf-458d-be72-b5f9521e94c3.png)
#### 6. Synchronous Data Tranmission(1) 설정값이 사진과 같은지 확인합니다. 다른 경우 설정값을 맞춰줍니다. 이후 Apply Flash Write(2) 버튼을 클릭합니다.
![ahrs_4](https://user-images.githubusercontent.com/85467544/155052026-1ce94fe9-6eb5-4e63-b9fc-0115f174113c.png)




***
