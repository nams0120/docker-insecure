# docker-insecure
인증서가 없는 상태에서 이미지 저장소를 사용하기 위해서는 "insecure registry" 설정을 해야된다 
도커 앤진 데몬의 설정파일인 'daemon.json' 에 'insecure registries' 설정 추가 
daemon.json path = /etc/docker
