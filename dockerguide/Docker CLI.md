## image



##### image 받기 (dockerhub에서 image 가져오는 방법)

$docker pull [name] 



##### image 확인

$docker images 



##### image를 실행시켜 컨테이너 만들기

$docker run [image name]

$docker run --name [컨테이너 이름지정] [image name]



##### image 삭제

$docker rmi [image name]





## Container



#####  실행중인 컨테이너  확인

$docker ps



##### 모든 컨테이너 확인

$docker ps -a 



##### 실행중인 컨테이너 끄기

$docker stop [컨테이너이름]



##### 실행중인 컨테이너 켜기

$docker start [컨테이너이름]



##### log  확인

$docker logs [컨테이너이름]



##### log 실시간 확인

$docker logs -f [컨테이너이름]



##### 컨테이너 삭제 (실행중인 컨테이너는 삭제 불가, stop 후 삭제)

$docker rm [컨테이너이름]



##### 컨테이너  강제 종료 및 삭제 

$docker rm --force [컨테이너이름]





## Publish (Publish a container's port to the host)

##### 컨테이너  강제 종료 및 삭제 

$docker run --name [컨테이너이름] -p [localhost #]:[container port#] [image 이름]





