# 1주차

### 1. 리눅스의 역사

1983년 9월 [리처드 스톨만](https://ko.wikipedia.org/wiki/리처드_스톨만)은 [GNU](https://ko.wikipedia.org/wiki/GNU) 프로젝트를 시작했다. GNU 프로젝트의 목적은 프리웨어로만 구성된 완전한 하나의 [유닉스-유사](https://ko.wikipedia.org/wiki/유닉스_계열) 시스템을 만드는 것이었다. 1989년, GNU는 시스템 라이브러리, 컴파일러, 텍스트 에디터, 셸 등의 커널을 제외한 시스템의 핵심적인 부분을 완성했다. 1990년 시작된 허드(Hurd) 커널은, 초기에는 [BSD](https://ko.wikipedia.org/wiki/BSD) 4.4-Lite 커널을 기반으로 개발하려 했으나, 원래의 BSD 커널을 개발했던 [버클리](https://ko.wikipedia.org/wiki/캘리포니아_대학교_버클리) 프로그래머들과의 협력이 이루어지지 않아 실패했다. 1987년 리처드 스톨만은 허드를 마하(Mach)라는 마이크로 커널을 기반으로 개발하려 했다. 그러나 마하는 예상외로 복잡한 구조를 가지고 있어서, 허드의 개발은 지체되었다.

그러던 중([1991년](https://ko.wikipedia.org/wiki/1991년)), 리눅스라는 이름의 또 다른 커널이 극적으로 등장하였다. 리눅스는 핀란드 헬싱키 대학의 대학원생인 [리누스 토발즈](https://ko.wikipedia.org/wiki/리누스_토발즈)가 취미 삼아 개발한 커널이었다. 토르발스는 원래 앤드루 스튜어트 타넨바움 교수가 운영 체제 디자인을 가르치기 위해 만든 교육용 유닉스인 [미닉스](https://ko.wikipedia.org/wiki/미닉스)를 사용하고 있었는데, 타넨바움이 미닉스를 다른 사람이 함부로 개조하지 못하도록 제한을 두자, 미닉스의 기능에 만족하지 못했던 토르발스는 새로운 운영 체제를 개발하고자 했다. 리눅스는 본래 운영 체제 위에서 실행되는 터미널 에뮬레이터였다. 초기에는 시리얼 포트를 이용한 간단한 신호를 주고 받는 작업밖에 할 수 없었지만, 토르발스는 디스크의 파일도 읽고, 쓰게 하고 싶었다. 이처럼 완전한 파일 제어가 가능해지자, 토르발스는 이것을 [포직스](https://ko.wikipedia.org/wiki/POSIX)(POSIX)에 호환되는 운영 체제 커널로 발전시키기로 마음먹고 이를 기반으로 리눅스를 개발하기 시작하였다. 리눅스의 첫 번째 버전인 0.01은 [1991년](https://ko.wikipedia.org/wiki/1991년) [9월 17일](https://ko.wikipedia.org/wiki/9월_17일) 인터넷을 통해 공개되었고, 첫 공식버전인 0.02는 같은해 10월에 발표되었다. 그 이후 지금까지, 전 세계 수천만의 개발자들이 리눅스 개발에 자발적으로 참여하고 있다. 초창기 리눅스는 설치와 부팅을 하기 위해서는, 미닉스와 같은 다른 운영 체제가 필요했다. 그러나 리로(lilo)와 같은 부트로더가 개발되고, GNU 프로젝트가 만들어낸 모든 유틸리티를 리눅스에서 사용할 수 있게 됨에 따라, 리눅스는 빠른 속도로 미닉스를 능가하게 되었다.

오늘날에도 여전히 토르발스는 리눅스 커널 개발을 지휘하고 있다. 현재 리눅스는 [X 윈도](https://ko.wikipedia.org/wiki/X_윈도_시스템)를 기반으로 한 [GNOME](https://ko.wikipedia.org/wiki/GNOME)이나 KDE와 같은 통합 데스크톱 환경과 수많은 응용 프로그램을 실행시킬 수 있으며, 많은 기업과 단체의 후원을 받고 있다.

[턱스](https://ko.wikipedia.org/wiki/턱스)(Tux)라는 이름의 펭귄은 [1996년](https://ko.wikipedia.org/wiki/1996년) 래리 유윙이 창조한 리눅스의 마스코트이다.

리눅스라는 이름은 리누스 토발즈가 아닌, [아리 람케](https://ko.wikipedia.org/w/index.php?title=아리_람케&action=edit&redlink=1)라는 사람이 지었다. 그는 ftp.funet.fi 사이트의 운영자였는데, 미리 리눅스라는 이름의 폴더를 ftp에 만들어, 토르발스가 커널을 올릴 수 있게 배려해 주었다. 토르발스는 원래 자신이 만든 커널의 이름을 프릭스(Freax)로 하려 했는데, 아리 람케의 주장으로 결국 리눅스라는 이름을 선택하게 되었다. 리눅스라는 이름의 어원은 리누스의 미닉스(LINUs' miniX)에서 나온 것으로 알려져 있다. 리눅스는 현재 리누스 토르발스의 등록상표(trade mark)이다.

리눅스가 인기를 얻자, 개방형 소스([오픈 소스](https://ko.wikipedia.org/wiki/오픈_소스))의 특성에 힘입어 다양한 리눅스 기반의 운영 체제가 쏟아져 나왔다. [페도라](https://ko.wikipedia.org/wiki/페도라), [우분투](https://ko.wikipedia.org/wiki/우분투) 등의 획기적인 운영 체제가 등장하였고, [구글](https://ko.wikipedia.org/wiki/구글)에서 배포하는 모바일 운영 체제인 [안드로이드](https://ko.wikipedia.org/wiki/안드로이드_(운영_체제))도 리눅스 기반의 오픈소스 운영 체제이다.



### 2. 리눅스의 간단한 명령어들

1. cd (change directory) : 작업 디렉터리 이동
2. ls : 현 디렉터리 파일 리스트 출력
3. pwd (print work dirctory) : 현재 작업 디렉터리 출력
4. cat (concatenation) : 파일을 문자열로 출력
5. mkdir (make directory) : 디렉터리 생성
6. rmdir (remove directory) : 디렉터리 제거
7. vi, nano : 파일 편집기
8. mv (move) : 파일 이동 또는 이름 변경
9. cp : 파일 복사
10. apt-get, yup : 패키지 매니저
11.  sudo : 관리자 권한으로 실행
12. top (or htop) : 컴퓨터 자원 사용량



### 3. 리눅스 시스템의 기본 디렉터리

https://blog.naver.com/PostView.nhn?blogId=itperson&logNo=220812561459&categoryNo=85&parentCategoryNo=0&viewDate=&currentPage=1&postListTopCurrentPage=1&from=postView&userTopListOpen=true&userTopListCount=10&userTopListManageOpen=false&userTopListCurrentPage=1

참조