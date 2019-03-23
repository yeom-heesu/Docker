# Docker
-------------
## Docker란?

컨테이너기반 오픈소스 가상화 플랫폼이다.
컨테이너와 가상머신은 비슷하면서도 매우 다르다.

가상머신(VM)은 host OS위에 guest OS가 동작하게 해주는 것을 의미한다.

하지만, 컨테이너는 격리된 공간에서 프로세스가 동작하는 기술을 의미한다.

docker는 컨테이너와 이미지로 구성되어 있다.

--------------

## image란?
컨테이너 실행에 필요한 파일과 설정값 등을 포함하고 있는것

컨테이너는 이미지를 실행한 상태와 추가 및 변경값을 컨테이너에 저장한다.

이미지 관리는 [Docker hub](https://hub.docker.com/) 혹은 [Docker Registry](https://docs.docker.com/registry/)에서 할수있다.

--------------
## Docker 설치하기
1. 리눅스에 아래의 명령어를 입력하면 root권한을 입력하고 설치가 완료된다.
```
curl -fs https://get.docker.com/ | sudo sh
```
2. 맥이나 윈도우즈에 설치하려면 [Docker for mac](https://docs.docker.com/docker-for-mac/) 또는 [Docker for windows](https://docs.docker.com/docker-for-windows/)를 설치하여야 한다.
