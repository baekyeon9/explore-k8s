## 

image 받기 (dockerhub에서 image 가져오는 방법)

$docker pull [name] 



image 확인

$docker images 



image를 실행시켜 컨테이너 만들기

$docker run [name]

$docker run --name [컨테이너 이름지정] [name]



실행중인 컨테이너  확인

$docker ps [name]



모든 컨테이너 확인

$docker ps -a 



실행중인 컨테이너 끄기

$docker stop [컨테이너이름]



실행중인 컨테이너 켜기

$docker start [컨테이너이름]



log  확인

$docker logs