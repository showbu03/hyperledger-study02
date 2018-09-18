# FastCampus HLF 1기 
## 사전 필요 사항 ##
* nodeJS v8.11.3 이상
* Docker 17.12.1-ce 이상
* HLF 1.2 Image
* yo (npm install -g yo generator-express-no-stress) 

## HLF 기반 Simple Balance API 개발 환경 구성
* 개발 소스 clone
```
$)cd ~ #홈디렉토리로 이동
$)mkdir github
$)git clone https://github.com/simon0210/hyperledger-study02.git
```
* nodeJS 모듈 설치
```
$)cd ~/github/hyperledger-study02
$)npm install
```

* HLF Basic 네트워크 구동
```
$) docker rm -f $(docker ps -aq) // 
```

## CouchDB
```
http://localhost:5984/_utils/#/_all_dbs
```
