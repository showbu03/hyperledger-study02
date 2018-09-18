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

````# Simple Balance API

Simple Balance API

## Hyperledger Network 개발 환경 구성
```
curl -sSL http://bit.ly/2ysbOFE | bash -s 1.2.0
```

## CouchDB
```
http://localhost:5984/_utils/#/_all_dbs
```

## Install It
```
npm install
npm install artillery -g
```

## Run It
#### Run in *development* mode:

```
npm run dev
```

#### Run in *production* mode:

```
npm run compile
npm start
```

#### Run tests:

```
npm test
```

#### Deploy to the Cloud
e.g. CloudFoundry

```
cf push ImPlatform
```

### Try It
* Point you're browser to [http://localhost:3000](http://localhost:3000)
* Invoke the example REST endpoint `curl http://localhost:3000/api/v1/examples`
   
# ImPlatform
````
