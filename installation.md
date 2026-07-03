# 설치 방법

## Windows 유저 설치 순서

1. 스팀판 히마츠부시 편 다운로드
2. 콘솔판 모드 패치 - [게시글 링크](https://gall.dcinside.com/mgallery/board/view/?id=higurashi&no=5560)
3. [배포 링크](https://github.com/goorub/HigurashiConsoleKR/releases/tag/%EB%B0%B0%ED%8F%AC)에서 `ConsoleArcsKorean{날짜}.zip` 파일을 받는다.
  - 링크에 패치 방법 설명 되어있음.


## Mac 유저 설치 순서

1. 스팀판 히마츠부시 편 다운로드
2. 콘솔판 모드 패치
  - 기본적으로 흐름은 [이 게시글 링크](https://gall.dcinside.com/mgallery/board/view/?id=higurashi&no=5560)를 참고하되,
  - 결과적으로는 [여기](https://wiki.07th-mod.com/Higurashi/Higurashi-Part-1---Voice-and-Graphics-Patch/)에 들어가서 설명을 읽고 설치하면 된다. 
3. [배포 링크](https://github.com/goorub/HigurashiConsoleKR/releases/tag/%EB%B0%B0%ED%8F%AC)에서 `ConsoleArcsKorean{날짜}_Mac.zip` 파일을 받는다.
  - 링크에 Mac 유저 패치 방법 확인


### Mac 콘솔판 모드 패치 하는방법

위 Mac 유저 설치 순서중 2번에 대한 세부 설명

<img width="943" height="674" alt="image" src="https://github.com/user-attachments/assets/4feec8a6-e6fb-4d20-9da6-bafc03c3ea1b" />

사진에 이어지는 설명을 요약하자면
1. OS 버전이 Monterey 이상이면 Python3을 따로 설치해주고 (설명에 링크 있음)
2. Mac용 인스톨러를 설치하고 압축 해제
3. install.command를 더블클릭해서 실행.
4. 아래로 내리면 나츠미 얼굴이 나오는데, 그걸 클릭하고 게임 경로 자동 감지되면 설치하기를 누른다.

권한 문제가 발생하면 아래 두가지중 하나를 시도. 

3-1) 터미널을 열고, install.command가 있는 폴더로 이동해서 터미널에 다음을 입력한다.
```bash
chmod +x install.command
```

다음으로 아래를 입력한다.
```bash
./install.command
```

3-2) [여기](https://osxdaily.com/2018/10/09/fix-operation-not-permitted-terminal-error-macos/) 참고해서 진행.

