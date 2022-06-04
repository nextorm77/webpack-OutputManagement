# Output Management

## github 해당 원격저장소 연결(SSH) 및 초기(?) push

$ git remote add origin '원격저장소 주소(SSH)'

## 처음 한번만 하면 됨

$ git push -u origin master

## Preparation

### node_modules 생성

$ npm i

### entry point

$ dist/index.html

## Setting up HtmlWebpackPlugin

### node_modules 생성

$ npm i

### entry point

$ dist/index.html

### node_modules 생성

## Cleaning up the /dist folder

오직 사용될 파일만 생성하기 위해 각 빌드(npm run build) 전에 /dist 폴더를 정리하는 것이 좋음

webpack.config.js 파일내 output.clean 옵션 설정으로 자동 처리
