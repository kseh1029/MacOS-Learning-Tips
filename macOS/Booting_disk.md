# Clorver & OpenCore 부팅디스크 만들기

## 1.GibMacOS-master

**1)USB MacOS 부팅디스크 만드는 방법.**

**-USB 파티션 나누기및 포멧 (16기가 이상 준비)**

**-윈도우창에서 => 검색 cmd 입력 => 관리자 권한으로 실행**

![Booting_disk/466b1675b6957be4ea0e042d9aaa1557.jpg](Booting_disk/466b1675b6957be4ea0e042d9aaa1557.jpg)

**diskpart** => Enter => **disk part** => Enter =>**list disk** =>**select disk 1** => Enter (USB 드라이브를 선택합니다)

=> **clean** => Enter => **create partition primary** => **Enter => format fs=fat32 quick** => Enter (**USB** 파티션끝)

![Booting_disk/7be316a2dfed0f31a169b62eb109ecd5.jpg](Booting_disk/7be316a2dfed0f31a169b62eb109ecd5.jpg)

![Booting_disk/2472e0efbe1039a6b88e4bc43b3d636a.jpg](Booting_disk/2472e0efbe1039a6b88e4bc43b3d636a.jpg)

**2) GibMacOS-master 다운 받는 방법**

다운로드 주소 : [https://github.com/corpnewt/gibMacOS](https://github.com/corpnewt/gibMacOS)

![Booting_disk/469d5115b034367384fab0002e863a9d.jpg](Booting_disk/469d5115b034367384fab0002e863a9d.jpg)

gibMacOS.bat (관리자 권한으로) **클릭**하면 cmd 창이 열림 y 선택합니다.

![Booting_disk/706399911fa97bdc478725bde5a336df.jpg](Booting_disk/706399911fa97bdc478725bde5a336df.jpg)

**3) MacOs 다운받는 방법**

![Booting_disk/ee184ef17f6f8a749daa8674c65e95ec.jpg](Booting_disk/ee184ef17f6f8a749daa8674c65e95ec.jpg)

-R클릭하면 전체 버전 보여줍니다.

-원하는 MacOs 다운로드 번호 입력하고 저는 1번 엔터 y 다운이 gibMacOS.bat/macOS Downloads 받아집니다.

FULL Install로 받으세요.

macOS Downloads 다 받아 지면 Enter 치고 빠져 나옵니다.

![https://x86.co.kr/files/attach/images/3704586/877/875/004/d3c45eb7b2df9759e6a4b6efb01b975f.jpg](https://x86.co.kr/files/attach/images/3704586/877/875/004/d3c45eb7b2df9759e6a4b6efb01b975f.jpg)

![Booting_disk/52ef94eca76980400cbbd69467ca9766.jpg](Booting_disk/52ef94eca76980400cbbd69467ca9766.jpg)

macOS Downloads폴더에 저장됩니다.

![Booting_disk/d3c45eb7b2df9759e6a4b6efb01b975f.jpg](Booting_disk/d3c45eb7b2df9759e6a4b6efb01b975f.jpg)

4) 부트로더 만드는 방법

-MakeInstall.bat파일 클릭하면 cmd 뜨면서 BOOTICEx64 파일

자동으로 만들어집니다.

![Booting_disk/cdf7115c90b481dbd73e78a2d0be25c9.jpg](Booting_disk/cdf7115c90b481dbd73e78a2d0be25c9.jpg)

- Scripts폴더에 BOOTICEx64 다운 받아집니다

![Booting_disk/960a99db08a12cc6fe3fac2828dbb525.jpg](Booting_disk/960a99db08a12cc6fe3fac2828dbb525.jpg)

엔터 치고 빠져나옵니다.

![Booting_disk/3e031bd448ee3a0fdfb355c869071585.jpg](Booting_disk/3e031bd448ee3a0fdfb355c869071585.jpg)

**1) USB 파티션에 / MacOS / OpenCore 부트로더 심기 / 넣기**

-다시 한번 관리자 권한으로 MakeInstall.bat파일 클릭하여 cmd창으로 ~ go

![Booting_disk/cdf7115c90b481dbd73e78a2d0be25c9%201.jpg](Booting_disk/cdf7115c90b481dbd73e78a2d0be25c9%201.jpg)

샘플1-1)

![Booting_disk/22210982478cc43781b1d5fa0ea1bca5.jpg](Booting_disk/22210982478cc43781b1d5fa0ea1bca5.jpg)

![Booting_disk/2effad5dcc9f4b4f00d20082d2e0d056.jpg](Booting_disk/2effad5dcc9f4b4f00d20082d2e0d056.jpg)

**1o**   **(숫자,영문소)** => Enter => **y** => Ente

1은 USB를 선택 0은 부트로더 선택

전체 설치에서 클로버 설치일때 USB 숫자 (1 이라 가정) 입력, 오픈코어 설치는 1O

1B 나 1BO 로 부트영역만 깔아봤는데.. 그렇게 해선 EFI 영역이 초기화가 안된다.

OpenCore 한번 켜고나면 결국 전체 재설치밖에 답이없다.

![Booting_disk/923acf5bf3f21e69012705ba51838e33.jpg](Booting_disk/923acf5bf3f21e69012705ba51838e33.jpg)

![Booting_disk/2ff9335e28589f9bb01ff08ca7fb6d6c.jpg](Booting_disk/2ff9335e28589f9bb01ff08ca7fb6d6c.jpg)

원도우 다운 받은 폴더에 이미지 **" RecoveryHDMetaDmg.pkg "**

/macOS Downloads / publicrelease /RecoveryHDMetaDmg.pkg

" RecoveryHDMetaDmg.pkg **" 마우스로 원클릭**하고

그창 홈 => **경로복사** cmd 창에 붙여(Ctrl + V) 넣는다

=> Ente

![Booting_disk/9db255f2d2c11d0f225ff3e1908c9477.jpg](Booting_disk/9db255f2d2c11d0f225ff3e1908c9477.jpg)

![Booting_disk/bfb0ae5e288ee38b0b50fb0b1a71fb37.jpg](Booting_disk/bfb0ae5e288ee38b0b50fb0b1a71fb37.jpg)

![Booting_disk/3eafa5888f3ec14cbc12900681b425e7.jpg](Booting_disk/3eafa5888f3ec14cbc12900681b425e7.jpg)

(시간이 좀 걸릴 수 있습니다) => 5분-10분 / 조금 있으면 완성됩니다.

![Booting_disk/dff44bad61ea8daf37e545581863e497.jpg](Booting_disk/dff44bad61ea8daf37e545581863e497.jpg)

Ente => 창 닫으세요.
