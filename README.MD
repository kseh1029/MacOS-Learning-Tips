# Clorver & OpenCore 부팅디스크 만들기
## 1.GibMacOS-master

**1)USB MacOS 부팅디스크 만드는 방법.**

**-USB 파티션 나누기및 포멧 (16기가 이상 준비)**

**-윈도우창에서 => 검색 cmd 입력 => 관리자 권한으로 실행**

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/f973dd7f-af24-4240-8ada-e5d4211b9642/466b1675b6957be4ea0e042d9aaa1557.jpg](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/f973dd7f-af24-4240-8ada-e5d4211b9642/466b1675b6957be4ea0e042d9aaa1557.jpg)

**diskpart** => Enter => **disk part** => Enter =>**list disk** =>**select disk 1** => Enter (USB 드라이브를 선택합니다)

=> **clean** => Enter => **create partition primary** => **Enter => format fs=fat32 quick** => Enter (**USB** 파티션끝)

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/d24d4ebd-47df-4ca6-ba27-a2d4fb491587/7be316a2dfed0f31a169b62eb109ecd5.jpg](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/d24d4ebd-47df-4ca6-ba27-a2d4fb491587/7be316a2dfed0f31a169b62eb109ecd5.jpg)

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/7093ffd2-4e8e-4d64-a2ea-5f195c7daba3/2472e0efbe1039a6b88e4bc43b3d636a.jpg](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/7093ffd2-4e8e-4d64-a2ea-5f195c7daba3/2472e0efbe1039a6b88e4bc43b3d636a.jpg)

**2) GibMacOS-master 다운 받는 방법**

다운로드 주소 : [https://github.com/corpnewt/gibMacOS](https://github.com/corpnewt/gibMacOS)

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/e9454e26-990d-4bd5-881a-4e7596d4415e/469d5115b034367384fab0002e863a9d.jpg](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/e9454e26-990d-4bd5-881a-4e7596d4415e/469d5115b034367384fab0002e863a9d.jpg)

gibMacOS.bat (관리자 권한으로) **클릭**하면 cmd 창이 열림 y 선택합니다.

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/ca635b3c-6c7a-4318-a92d-1cdc498483e0/706399911fa97bdc478725bde5a336df.jpg](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/ca635b3c-6c7a-4318-a92d-1cdc498483e0/706399911fa97bdc478725bde5a336df.jpg)

**3) MacOs 다운받는 방법**

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/08bd73f6-6540-498d-bac9-59d01824eac6/ee184ef17f6f8a749daa8674c65e95ec.jpg](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/08bd73f6-6540-498d-bac9-59d01824eac6/ee184ef17f6f8a749daa8674c65e95ec.jpg)

-R클릭하면 전체 버전 보여줍니다.

-원하는 MacOs 다운로드 번호 입력하고 저는 1번 엔터 y 다운이 gibMacOS.bat/macOS Downloads 받아집니다.

FULL Install로 받으세요.

macOS Downloads 다 받아 지면 Enter 치고 빠져 나옵니다.

![https://x86.co.kr/files/attach/images/3704586/877/875/004/d3c45eb7b2df9759e6a4b6efb01b975f.jpg](https://x86.co.kr/files/attach/images/3704586/877/875/004/d3c45eb7b2df9759e6a4b6efb01b975f.jpg)

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/dbe48649-b979-40e9-b83e-fbc1312e5bac/52ef94eca76980400cbbd69467ca9766.jpg](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/dbe48649-b979-40e9-b83e-fbc1312e5bac/52ef94eca76980400cbbd69467ca9766.jpg)

macOS Downloads폴더에 저장됩니다.

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/d23942ad-5b1f-437f-b54d-50bc95ff27af/d3c45eb7b2df9759e6a4b6efb01b975f.jpg](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/d23942ad-5b1f-437f-b54d-50bc95ff27af/d3c45eb7b2df9759e6a4b6efb01b975f.jpg)

4) 부트로더 만드는 방법

-MakeInstall.bat파일 클릭하면 cmd 뜨면서 BOOTICEx64 파일

자동으로 만들어집니다.

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/a19b7394-5fa2-4311-ad93-d9c60a6078a4/cdf7115c90b481dbd73e78a2d0be25c9.jpg](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/a19b7394-5fa2-4311-ad93-d9c60a6078a4/cdf7115c90b481dbd73e78a2d0be25c9.jpg)

- Scripts폴더에 BOOTICEx64 다운 받아집니다

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/48273d8d-b9b0-4125-be41-3eb0b6c9b1e3/960a99db08a12cc6fe3fac2828dbb525.jpg](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/48273d8d-b9b0-4125-be41-3eb0b6c9b1e3/960a99db08a12cc6fe3fac2828dbb525.jpg)

엔터 치고 빠져나옵니다.

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/c1524142-fa90-422f-9809-c36b2bf1aa2b/3e031bd448ee3a0fdfb355c869071585.jpg](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/c1524142-fa90-422f-9809-c36b2bf1aa2b/3e031bd448ee3a0fdfb355c869071585.jpg)

**1) USB 파티션에 / MacOS / OpenCore 부트로더 심기 / 넣기**

-다시 한번 관리자 권한으로 MakeInstall.bat파일 클릭하여 cmd창으로 ~ go

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/c7965145-4eb1-47bc-af40-bb72190cc7a3/cdf7115c90b481dbd73e78a2d0be25c9.jpg](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/c7965145-4eb1-47bc-af40-bb72190cc7a3/cdf7115c90b481dbd73e78a2d0be25c9.jpg)

샘플1-1)

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/78cc2368-f991-4781-84ab-11cb0bf92422/22210982478cc43781b1d5fa0ea1bca5.jpg](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/78cc2368-f991-4781-84ab-11cb0bf92422/22210982478cc43781b1d5fa0ea1bca5.jpg)

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/c12e0d74-6219-4c31-9e74-2b45a076c0f9/2effad5dcc9f4b4f00d20082d2e0d056.jpg](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/c12e0d74-6219-4c31-9e74-2b45a076c0f9/2effad5dcc9f4b4f00d20082d2e0d056.jpg)

**1o**   **(숫자,영문소)** => Enter => **y** => Ente

1은 USB를 선택 0은 부트로더 선택

전체 설치에서 클로버 설치일때 USB 숫자 (1 이라 가정) 입력, 오픈코어 설치는 1O

1B 나 1BO 로 부트영역만 깔아봤는데.. 그렇게 해선 EFI 영역이 초기화가 안된다.

OpenCore 한번 켜고나면 결국 전체 재설치밖에 답이없다.

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/d3447655-bd03-4618-8d44-ebfc4d631198/923acf5bf3f21e69012705ba51838e33.jpg](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/d3447655-bd03-4618-8d44-ebfc4d631198/923acf5bf3f21e69012705ba51838e33.jpg)

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/0cca0c3f-14ee-4c02-9816-28d9fd25ede8/2ff9335e28589f9bb01ff08ca7fb6d6c.jpg](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/0cca0c3f-14ee-4c02-9816-28d9fd25ede8/2ff9335e28589f9bb01ff08ca7fb6d6c.jpg)

원도우 다운 받은 폴더에 이미지 **" RecoveryHDMetaDmg.pkg "**

/macOS Downloads / publicrelease /RecoveryHDMetaDmg.pkg

" RecoveryHDMetaDmg.pkg **" 마우스로 원클릭**하고

그창 홈 => **경로복사** cmd 창에 붙여(Ctrl + V) 넣는다

=> Ente

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/5b177c8b-2f50-4d1d-b25c-d12d32ffc9ec/9db255f2d2c11d0f225ff3e1908c9477.jpg](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/5b177c8b-2f50-4d1d-b25c-d12d32ffc9ec/9db255f2d2c11d0f225ff3e1908c9477.jpg)

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/754dd348-b20b-4d13-a129-fb189160ea21/bfb0ae5e288ee38b0b50fb0b1a71fb37.jpg](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/754dd348-b20b-4d13-a129-fb189160ea21/bfb0ae5e288ee38b0b50fb0b1a71fb37.jpg)

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/2009dbaf-6cab-4617-bb9d-8721b6bb207e/3eafa5888f3ec14cbc12900681b425e7.jpg](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/2009dbaf-6cab-4617-bb9d-8721b6bb207e/3eafa5888f3ec14cbc12900681b425e7.jpg)

(시간이 좀 걸릴 수 있습니다) => 5분-10분 / 조금 있으면 완성됩니다.

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/ee9e26e1-7e00-4ba5-bd32-8033e485d6b8/dff44bad61ea8daf37e545581863e497.jpg](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/ee9e26e1-7e00-4ba5-bd32-8033e485d6b8/dff44bad61ea8daf37e545581863e497.jpg)

Ente => 창 닫으세요.
