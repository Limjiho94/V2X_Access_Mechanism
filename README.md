# DID와 VC기반 차량 등록자격증명서 발급 시스템
      
본 시스템은 DID 기반 차량 등록자격증명서 발급 시스템 Demo다.
 

## 개요
Evernym 사의 오픈소스 및 Sovrin 원장과 Connect.me 어플리케이션을 활용하여 모바일증명서 발급 및 검증 시스템울 구현하였다.

발급기관은 등록자격증명서 발급기관(Enrollment CA), 검증기관은 익명인증서 발급기관(Pseudonym CA), 사용자는 Alice로 가정한다.

issuer 디렉터리의 서비스 주체는 Enrollment CA, verifier 디렉터리의 서비스 주체는 Pseudonym CA 이다.

![image](https://user-images.githubusercontent.com/94879566/204530971-1a85e7df-4d84-45e3-a80d-821d0ba9ab63.png)


[시스템 아키텍처]

## 개발 환경
OS : Ubuntu 18.04 LTS

Docker : 20.10.7

Mobile Application : Connect.me

Open Source : Evernym verity-sdk(https://github.com/evernym/verity-sdk)


변경사항은 https://github.com/Limhji94/V2X_Project를 통해 업데이트 됩니다.

