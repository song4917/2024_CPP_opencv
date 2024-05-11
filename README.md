# C++에서 OpenCV 활용하기

[ 영상 크기가 커서 유튜브 일부 공개 영상 링크로 대채하겠습니다 ]

#### 입력 및 테스트 영상 - https://youtu.be/V9EW-VqopXI






## 1. Visual Studio를 실행하소 새로운 프로젝트를 생성하거나 기존 프로젝트 열기.

## 2. 프로젝트에 대해 우틀릭하여 "속성(Properties)"을 선택합니다.
   
## 3. C/C++ -> C/C++ → 일반 → 추가 포함 디렉터리(Additional Include Directories)

  ### - 설치된 OpenCV 폴더 내의 `include` 디렉터리 경로를 추가합니다.]

  ### - 예: `C:\opencv\build\include`

## 4. 링커 → 일반 → 추가 라이브러리 디렉터리(Additional Library Directories)

  ### - 빌드 환경에 맞는 lib 폴더 경로를 추가

  ### 예: `C:\opencv\build\x64\vc16\lib` (64비트 환경일 경우)

## 5.링커 → 입력 → 추가 종속성(Additional Dependencies)

  ### - 사용하려는 OpenCV 모듈에 맞는 .lib 파일들을 추가

  ### (opencv_world490d.lib 디버그 모드에서는 'd' 접미사가 붙은 라이브러리 사용)

# □ 윈도우 시스템 환경 변수 설정

## ○ 시스템의 환경 변수에 OpenCV의 bin 디렉터리를 PATH에 추가

  ### - 예: `C:\opencv\build\x64\vc16\bin`

  ### - 이렇게 하면 프로그램 실행 시 OpenCV DLL들이 시스템에 의해 찾을 수 있음

# ​□ 빌드 및 실행

### - 오류: dll 을 현재 폴더에 복사하기

### - 솔루션을 빌드하고 실행하여 설정이 올바르게 되었는지 확인
