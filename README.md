# HLSL Development Cookbook Source Codes

WIP ( Work in Progress )  

- 레거시 프로젝트 위한 DirectX 11 직무 교육( OJT, On the job Training )을 위해서 생성 하였습니다.  
- Visual Studio 2022 Community  
- DirectX SDK ( June 2010 )


## 책 관련 링크  

<img src="https://content.packt.com/_/image/original/B01100/cover_image.jpg" alt="" height="256px" align="right">

- [HLSL Development Cookbook [ 원서 ]](https://www.packtpub.com/en-us/product/hlsl-development-cookbook-9781849694209)  

- [HLSL 프로그래밍 [ 번역서 ]](http://acornpub.co.kr/book/hlsl-cookbook)  


## 개발 및 테스트 환경  

- 시스템 ( Computer System )  

  - AMD Ryzen 9 7900X 12-Core Processor
  - 32G RAM
  - NVIDIA Geforce RTX 3060 12GB
  - SSD 2TB
  - Windows 11 64bit Korean

- 컴파일러 및 링커 ( Compiler , Linker )  

  - [Visual Studio Community 2022](https://visualstudio.microsoft.com/ko/free-developer-offers/)  
    - C++를 사용한 데스크톱 개발  
    - C++를 사용한 게임 개발  ( DirectX SDK 포함되어 있음 )


## 사용된 패키지 목록

- DirectX SDK ( June 2010 )  
  - https://www.microsoft.com/en-us/download/details.aspx?id=6812
  - [DXSDK_Jun10.exe](https://download.microsoft.com/download/a/e/7/ae743f1f-632b-4809-87a9-aa1bb3458e31/DXSDK_Jun10.exe)  

- DXUT11  
  - https://github.com/microsoft/DirectX-SDK-Samples/tree/main/C%2B%2B/DXUT11  


## ...

- ...

- ...



---
---
---


# HLSL-Development-Cookbook
http://www.acornpub.co.kr/book/hlsl-cookbook 에서 다운로드 받은 HLSL Development Cookbook 도서의 소스 코드를 VC++ 2008 에서 빌드할 수 있도록 수정하는 프로젝트입니다.

http://www.acornpub.co.kr/book/hlsl-cookbook 에서 다운로드 받은 HLSL Development Cookbook 도서의 소스 코드는 VC++ 2010 에서 빌드할 수 있도록 개발된 것 같고 VC++ 2008 에서 빌드하려면 빌드 환경을 다시 구성해야 하므로 VC++ 2008 에서 빌드할 수 있도록 빌드 환경을 다시 구성하는 프로젝트를 시작하게 되었습니다.

수작업으로 VC++ 2008 솔루션 및 프로젝트를 생성하고 빌드 환경을 구성하는 것은 다소 번거로움이 있어서 소스 코드 폴더를 지정하면 해당 소스 코드 폴더에 VC++ 2008 술루션 파일 및 프로젝트 파일을 자동으로 생성하고 빌드 환경을 구성해 주는 CreateVC2008Project 프로그램을 개발하였습니다. CreateVC2008Project 프로그램의 소스 코드는 CreateVC2008Project 폴더를 참고하세요.

본 프로젝트의 소스 코드를 빌드하려면 DirectX SDK(June 2010) 이 설치되어 있어야 하고 DirectX SDK(June 2010) 의 기본 설치 폴더인 "C:\Program Files (x86)\Microsoft DirectX SDK (June 2010)" 폴더에 설치되어 있어야 합니다. 또한 VC++ 2008 이 설치되어 있어야 합니다.

본 프로젝트를 진행하는 개발자 정보는 다음과 같습니다.

* 개발자 블로그: http://blog.naver.com/websearch
