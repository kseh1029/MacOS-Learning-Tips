# Clorver & OpenCore 부팅디스크 만들기
빨간색: 중요
파란색: 추가 사항
초록색: 입력하는 코드들
1. GibMacOS다운로드하기
https://github.com/corpnewt/gibMacOS
MacOS(모든 버전 호환) 설치 미디어 만들기(Windows, MacOS, Linux) - 커스텀맥(해킨) 강좌&Tip - X86.CO.KR
Download Zip을 클릭한후 저장한 압축파일을 압축헤제합니다
2. 설치 이미지 다운로드하기
운영체제에 맞게 이동하세요
[Windows]
MacOS(모든 버전 호환) 설치 미디어 만들기(Windows, MacOS, Linux) - 커스텀맥(해킨) 강좌&Tip - X86.CO.KR
1.  gibMacOS를 클릭합니다
MacOS(모든 버전 호환) 설치 미디어 만들기(Windows, MacOS, Linux) - 커스텀맥(해킨) 강좌&Tip - X86.CO.KR
* 옵션을 선택할수 있습니다.(일반 설치자들은 뒤로 넘어가기)
-  m : macOS 표시 버전 변경
-  c  :  macOS가 표시되는 카탈로그 변경(Customer, publicrelease(정식 버전), public(퍼블릭베타). developer(디벨로퍼 베타))
MacOS(모든 버전 호환) 설치 미디어 만들기(Windows, MacOS, Linux) - 커스텀맥(해킨) 강좌&Tip - X86.CO.KRMacOS(모든 버전 호환) 설치 미디어 만들기(Windows, MacOS, Linux) - 커스텀맥(해킨) 강좌&Tip - X86.CO.KR
2.  r을 입력합니다
MacOS(모든 버전 호환) 설치 미디어 만들기(Windows, MacOS, Linux) - 커스텀맥(해킨) 강좌&Tip - X86.CO.KR
3.  다운로드할 macOS버전의 번호를 입력합니다
MacOS(모든 버전 호환) 설치 미디어 만들기(Windows, MacOS, Linux) - 커스텀맥(해킨) 강좌&Tip - X86.CO.KR
4. 완료되면 enter를 입력합니다.
5. q를 입력하고 창을 닫습니다.
MacOS(모든 버전 호환) 설치 미디어 만들기(Windows, MacOS, Linux) - 커스텀맥(해킨) 강좌&Tip - X86.CO.KR
6. 밑의 설치미디어 만들기로 가주세요
[MacOS]

MacOS(모든 버전 호환) 설치 미디어 만들기(Windows, MacOS, Linux) - 커스텀맥(해킨) 강좌&Tip - X86.CO.KR
1. gibMacOS.command를 클릭합니다(오른쪽 클릭후 열기 클릭합니다)
* 옵션을 선택할수 있습니다.(일반 설치자들은 뒤로 넘어가기)
-  m : macOS 표시 버전 변경
-  c  :  macOS가 표시되는 카탈로그 변경(Customer, publicrelease(정식 버전), public(퍼블릭베타). developer(디벨로퍼 베타))
MacOS(모든 버전 호환) 설치 미디어 만들기(Windows, MacOS, Linux) - 커스텀맥(해킨) 강좌&Tip - X86.CO.KRMacOS(모든 버전 호환) 설치 미디어 만들기(Windows, MacOS, Linux) - 커스텀맥(해킨) 강좌&Tip - X86.CO.KR
2. 다운로드할 macOS버전의 번호를 입력합니다
MacOS(모든 버전 호환) 설치 미디어 만들기(Windows, MacOS, Linux) - 커스텀맥(해킨) 강좌&Tip - X86.CO.KR
3.  완료되면 enter를 입력합니다
4.q를 입력해 창을 닫습니다.
5. 밑의 설치미디어 만들기로 가주세요
[Linux]
1. python을 설치합니다.
sudo apt-get install python
MacOS(모든 버전 호환) 설치 미디어 만들기(Windows, MacOS, Linux) - 커스텀맥(해킨) 강좌&Tip - X86.CO.KR
2. gibmacos폴더로 이동하여 다음 명령어를 입력합니다
python gibMacOS.command -r
MacOS(모든 버전 호환) 설치 미디어 만들기(Windows, MacOS, Linux) - 커스텀맥(해킨) 강좌&Tip - X86.CO.KR
* 옵션을 선택할수 있습니다.(일반 설치자들은 뒤로 넘어가기)
-  m : macOS 표시 버전 변경
-  c  :  macOS가 표시되는 카탈로그 변경(Customer, publicrelease(정식 버전), public(퍼블릭베타). developer(디벨로퍼 베타))
MacOS(모든 버전 호환) 설치 미디어 만들기(Windows, MacOS, Linux) - 커스텀맥(해킨) 강좌&Tip - X86.CO.KRMacOS(모든 버전 호환) 설치 미디어 만들기(Windows, MacOS, Linux) - 커스텀맥(해킨) 강좌&Tip - X86.CO.KR
3. r을 입력합니다.    (R. Toggle Recovery-Only (Currently On)일때는 입력하지 않습니다)
MacOS(모든 버전 호환) 설치 미디어 만들기(Windows, MacOS, Linux) - 커스텀맥(해킨) 강좌&Tip - X86.CO.KR
4. 다운로드하는 MacOS의 번호를 입력합니다
 MacOS(모든 버전 호환) 설치 미디어 만들기(Windows, MacOS, Linux) - 커스텀맥(해킨) 강좌&Tip - X86.CO.KR
5. enter를 입력합니다.
6. q를 입력해 창을 닫습니다.
7. 밑의 설치미디어 만들기로 가주세요
3. 설치미디어 만들기
[Windows]
1. gibmacos>macOS Downloads>customer/public/publicreleases/deceloper>이상한 이름의 폴더로 이동해서 폴더의 경로를 복사해주세요
MacOS(모든 버전 호환) 설치 미디어 만들기(Windows, MacOS, Linux) - 커스텀맥(해킨) 강좌&Tip - X86.CO.KR
2. 다시 gibmacos폴더로 돌아와 makeinstall을 관리자 권한으로 실행시킵니다
MacOS(모든 버전 호환) 설치 미디어 만들기(Windows, MacOS, Linux) - 커스텀맥(해킨) 강좌&Tip - X86.CO.KR
      
    [Clover부트로더]
         1.  USB의 번호를 입력합니다.
            MacOS(모든 버전 호환) 설치 미디어 만들기(Windows, MacOS, Linux) - 커스텀맥(해킨) 강좌&Tip - X86.CO.KR
        2. y를 입력합니다.
            MacOS(모든 버전 호환) 설치 미디어 만들기(Windows, MacOS, Linux) - 커스텀맥(해킨) 강좌&Tip - X86.CO.KR
        오류가 나면 enter를 입력하고 다시 시도해주세요
            MacOS(모든 버전 호환) 설치 미디어 만들기(Windows, MacOS, Linux) - 커스텀맥(해킨) 강좌&Tip - X86.CO.KR
        3. 아까 복사해둔 경로를 붙여넣기 합니다.
            MacOS(모든 버전 호환) 설치 미디어 만들기(Windows, MacOS, Linux) - 커스텀맥(해킨) 강좌&Tip - X86.CO.KR
        4. 작업이 완료되면 enter를 입력합니다.
            MacOS(모든 버전 호환) 설치 미디어 만들기(Windows, MacOS, Linux) - 커스텀맥(해킨) 강좌&Tip - X86.CO.KR
        5. q를 입력한후 창을 닫습니다
        6. BOOT디스크에 EFI파일을 복사합니다.
            MacOS(모든 버전 호환) 설치 미디어 만들기(Windows, MacOS, Linux) - 커스텀맥(해킨) 강좌&Tip - X86.CO.KR
    [OpenCore 부트로더]
         1.  USB의 번호+o(알파벳)을 입력합니다.
            MacOS(모든 버전 호환) 설치 미디어 만들기(Windows, MacOS, Linux) - 커스텀맥(해킨) 강좌&Tip - X86.CO.KR
        2. y를 입력합니다.
            MacOS(모든 버전 호환) 설치 미디어 만들기(Windows, MacOS, Linux) - 커스텀맥(해킨) 강좌&Tip - X86.CO.KR
        오류가 나면 enter를 입력하고 다시 시도해주세요
            MacOS(모든 버전 호환) 설치 미디어 만들기(Windows, MacOS, Linux) - 커스텀맥(해킨) 강좌&Tip - X86.CO.KR
        3. 아까 복사해둔 경로를 붙여넣기 합니다.
            MacOS(모든 버전 호환) 설치 미디어 만들기(Windows, MacOS, Linux) - 커스텀맥(해킨) 강좌&Tip - X86.CO.KR
        4. 작업이 완료되면 enter를 입력합니다.
            MacOS(모든 버전 호환) 설치 미디어 만들기(Windows, MacOS, Linux) - 커스텀맥(해킨) 강좌&Tip - X86.CO.KR
        5. q를 입력한후 창을 닫습니다
        6. BOOT디스크에 EFI파일을 복사합니다.
            MacOS(모든 버전 호환) 설치 미디어 만들기(Windows, MacOS, Linux) - 커스텀맥(해킨) 강좌&Tip - X86.CO.KR
[MacOS]
1. gibmacos>macOS Downloads>customer/public/publicreleases/developer>이상한 이름의 폴더로 이동합니다
1/2번 방법 자신의 경우에 따라 이동 
1번 방법
1) Install Assistant를 클릭합니다.
MacOS(모든 버전 호환) 설치 미디어 만들기(Windows, MacOS, Linux) - 커스텀맥(해킨) 강좌&Tip - X86.CO.KR
2) 계속, 설치를 누릅니다
MacOS(모든 버전 호환) 설치 미디어 만들기(Windows, MacOS, Linux) - 커스텀맥(해킨) 강좌&Tip - X86.CO.KR
       1. 업데이트 설치하실 분들은 런치패드, 응용프로그램 폴더에서 macOS "자신이 고른 OS" 설치 프로그램을 클릭하여 진행합니다
            MacOS(모든 버전 호환) 설치 미디어 만들기(Windows, MacOS, Linux) - 커스텀맥(해킨) 강좌&Tip - X86.CO.KRMacOS(모든 버전 호환) 설치 미디어 만들기(Windows, MacOS, Linux) - 커스텀맥(해킨) 강좌&Tip - X86.CO.KR
            MacOS(모든 버전 호환) 설치 미디어 만들기(Windows, MacOS, Linux) - 커스텀맥(해킨) 강좌&Tip - X86.CO.KR
        2. 설치 미디어를 만드실 분은 
            1) USB를 MyVolume으로 포맷합니다.
                    MacOS(모든 버전 호환) 설치 미디어 만들기(Windows, MacOS, Linux) - 커스텀맥(해킨) 강좌&Tip - X86.CO.KRMacOS(모든 버전 호환) 설치 미디어 만들기(Windows, MacOS, Linux) - 커스텀맥(해킨) 강좌&Tip - X86.CO.KR     
            1). 다음의 명령어를 터미널에 입력합니다.
                MacOS(모든 버전 호환) 설치 미디어 만들기(Windows, MacOS, Linux) - 커스텀맥(해킨) 강좌&Tip - X86.CO.KR
sudo /Applications/Install\ macOS\ "자신이 설치할 OS(ex: Catalina, Mojave, High\ Sierra, Big\ Sur\ Beta".app/Contents/Resources/createinstallmedia --volume /Volumes/MyVolume
            2)   EFI 폴더를 마운트해 EFI 파일들을 집어넣습니다.
                MacOS(모든 버전 호환) 설치 미디어 만들기(Windows, MacOS, Linux) - 커스텀맥(해킨) 강좌&Tip - X86.CO.KRMacOS(모든 버전 호환) 설치 미디어 만들기(Windows, MacOS, Linux) - 커스텀맥(해킨) 강좌&Tip - X86.CO.KRMacOS(모든 버전 호환) 설치 미디어 만들기(Windows, MacOS, Linux) - 커스텀맥(해킨) 강좌&Tip - X86.CO.KR
2번방법
1) BaseSystem.dmg와 BaseSystem.chunklist 파일을 복사합니다.
MacOS(모든 버전 호환) 설치 미디어 만들기(Windows, MacOS, Linux) - 커스텀맥(해킨) 강좌&Tip - X86.CO.KR
2) USB를 포맷합니다.(이름은 마음대로)
MacOS(모든 버전 호환) 설치 미디어 만들기(Windows, MacOS, Linux) - 커스텀맥(해킨) 강좌&Tip - X86.CO.KRMacOS(모든 버전 호환) 설치 미디어 만들기(Windows, MacOS, Linux) - 커스텀맥(해킨) 강좌&Tip - X86.CO.KR     
3) com.apple.recovery.boot폴더를 생성합니다.
MacOS(모든 버전 호환) 설치 미디어 만들기(Windows, MacOS, Linux) - 커스텀맥(해킨) 강좌&Tip - X86.CO.KR

4) 폴더안에 아까 복사한 항목들을 붙여넣기합니다.
MacOS(모든 버전 호환) 설치 미디어 만들기(Windows, MacOS, Linux) - 커스텀맥(해킨) 강좌&Tip - X86.CO.KR
5) EFI폴더에 EFI파일들을 집어넣습니다.
      MacOS(모든 버전 호환) 설치 미디어 만들기(Windows, MacOS, Linux) - 커스텀맥(해킨) 강좌&Tip - X86.CO.KRMacOS(모든 버전 호환) 설치 미디어 만들기(Windows, MacOS, Linux) - 커스텀맥(해킨) 강좌&Tip - X86.CO.KRMacOS(모든 버전 호환) 설치 미디어 만들기(Windows, MacOS, Linux) - 커스텀맥(해킨) 강좌&Tip - X86.CO.KR 
[Linux]
1. 디스크를 포맷합니다(이름은 아무렇게나, 사진과 달리 두개로 분할해 하나는 EFI파티션으로 사용)
MacOS(모든 버전 호환) 설치 미디어 만들기(Windows, MacOS, Linux) - 커스텀맥(해킨) 강좌&Tip - X86.CO.KR
2. 다음 명령어를 입력합니다.( /dev/sdc1이 아니라 자신의USB가 마운트 된 곳으로 입력)
sudo mkfs.vfat -F 32 -n "OPENCORE" /dev/자신의USB가 마운트 된곳
MacOS(모든 버전 호환) 설치 미디어 만들기(Windows, MacOS, Linux) - 커스텀맥(해킨) 강좌&Tip - X86.CO.KR
3. 이 명령어로 7zip을 설치합니다
sudo apt-get install p7zip-full(apt-get install은 우분투, 데비안의 경우이며 다른 리눅스의 경우 설치법이 다를 수 있음)MacOS(모든 버전 호환) 설치 미디어 만들기(Windows, MacOS, Linux) - 커스텀맥(해킨) 강좌&Tip - X86.CO.KR
4) gibmacos>macOS Downloads>customer/public/publicreleases/deceloper>이상한 이름의 폴더로 이동한 후 다음 명령어를 입력합니다
7z e -txar *.pkg *.dmg; 7z e *.dmg */Base*
 MacOS(모든 버전 호환) 설치 미디어 만들기(Windows, MacOS, Linux) - 커스텀맥(해킨) 강좌&Tip - X86.CO.KR
5) 디스크로 이동해 com.apple.recovery.boot폴더를 만듭니다.
mkdir com.apple.recovery.boot
MacOS(모든 버전 호환) 설치 미디어 만들기(Windows, MacOS, Linux) - 커스텀맥(해킨) 강좌&Tip - X86.CO.KR
6) gibmacos>macOS Downloads>customer/public/publicreleases/deceloper>이상한 이름의 폴더로 이동해 BaseSystem.dmg와 BaseSystem.chunklist 파일을 복사합니다.
MacOS(모든 버전 호환) 설치 미디어 만들기(Windows, MacOS, Linux) - 커스텀맥(해킨) 강좌&Tip - X86.CO.KR
7) USB의 com.apple.recovery.boot폴더에 붙여넣기합니다.
MacOS(모든 버전 호환) 설치 미디어 만들기(Windows, MacOS, Linux) - 커스텀맥(해킨) 강좌&Tip - X86.CO.KR
8) EFI파티션에 EFI파일들을 집어넣습니다.
