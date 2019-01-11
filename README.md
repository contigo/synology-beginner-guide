# 시놀로지 입문자를 위한 가이드

## 소개
시놀로지 사용자를 위한 정보를 모아두기 위한 저장소입니다.  
나아가 개인 리눅스 서버에서 필요한 정보까지를 잘 정돈하고 싶습니다.  
더 좋은 자료와 제안이 있다면 **풀리퀘스트(PR)** 은 언제나 환영입니다.  
또한 저작권에 위배되는 자료와 정보를 직접적으로 다루지 않습니다.  

## 시놀로지 최초 설치 방법
 시놀로지 공식 다운로드 센터는 친절하고 직관적인 기본 설치 방법을 다룹니다.  
 기본적으로 공유기 사용이 요구되며..   
 1. 하드디스크 장착 후 
 2. 랜선 & 전원 연결
 3. <http://find.synology.com> 를 접속

 의 과정만으로도 초보자도 손쉽게 설치가 가능합니다.  
  이외의 유틸리티는 하단 공식 홈페이지에서 다운로드 받아 설치할수 있습니다.


- [시놀로지 다운로드 센터](https://www.synology.com/ko-kr/support/download)


## 들어가면서..
네트워크 저장소를 뜻하는 NAS(나스)는 개인정보를 다루므로 보안에 민감합니다.  
나스를 내가 원하는 기능을 추가하며 사용하기 위해 기본적인 **네트워킹** 과 그에 알맞은 **보안지식**의 **습득이 선행**되어야 합니다.

**네트워킹과 보안지식** 은 그 범위가 넓고 방대하므로 별도의 페이지로 대체합니다.  
그 페이지는 하단을 클릭해주세요.



### [네트워킹과 보안지식](https://github.com/liante0904/synology-beginner-guide/blob/master/NETWORK.md)



## 설치 및 세팅 방법

### Docker
- [시놀로지 공식 홈페이지 - Docker 설치 가능 모델](https://www.synology.com/ko-kr/dsm/packages/Docker)
- [github nicewoong님의 Docker 사용법](https://nicewoong.github.io/development/2017/10/09/basic-usage-for-docker/)
  - 시놀로지 GUI Docker가 아닌 CLI 사용법(설치 이외에 사용법 동일)

### Plex
- [pagein.net의 plex설치 (네이티브)](https://pagein.net/synology-xpenology-plex-media-server-%EA%B5%AC%EC%B6%95%ED%95%98%EA%B8%B0/)

### Tvheadend
- [Docker 설치부터 Tvheadend 구축까지 lightinglife님 블로그](http://lightinglife.tistory.com/174)


### Reverse Proxy(역방향 프록시)
- [클리앙 명량중년님의 시놀로지 역방향 프록시로 port 번호 없이 사용하기](https://www.clien.net/service/board/cm_nas/10938224)

### SSL(HTTPS)
- [클리앙 철이씨님의 무료 duckdns를 시놀로지에 등록해 봅시다](https://www.clien.net/service/board/cm_nas/9177427)


### vi
- [devfalledinmac님의 vi 사용법](http://devfalledinmac.tistory.com/12)
