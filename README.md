# mosphere

### Environment

###### NodeJS 8.11.3 LTS
  - 설치 파일 다운로드 : <https://nodejs.org/en/>
  - npm @5.6.0 : ~Users/AppData/Roaming/npm/node_modules/npm
  
###### Typescript
  - $ npm install -g typescript
  - typescript@2.9.2

###### Angular, Angular CLI 
  - $ npm i -g @angular/cli
  - @angular/cli@6.0.8
  - $ ng --version

  
Package                     | Version 
:-----------------------|:--------
@angular-devkit/architect   |0.6.8    
@angular-devkit/core        |0.6.8    
@angular-devkit/schematics  |0.6.8    
@schematics/angular         |0.6.8    
@schematics/update          |0.6.8    
rxjs                        |6.2.1    

###### Meteor (MongoDB)

###### Ionic

###### Electron



### Project 생성

  - ($ npm set legacy-bundling=false)
  - $ ng new core
  - $ cd core
  - $ ng serve -o

브라우저에서 `localhost:4200` 페이지 확인할 수 있다.

주) `npm set legacy-bundling=true` 로 설정이 되 있는 경우 실행이 되지 않으니,
 이런 경우 다음과 같이 다시 시도해 본다.

  - $ ng new core --skip-install
  - $ cd core
  - $ npm install --legacy-bundling=false
  - $ ng serve -o

[angular2 cli로 프로젝트 시작하기](https://medium.com/witinweb/angular-2-cli-%EB%A1%9C-%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8-%EC%8B%9C%EC%9E%91%ED%95%98%EA%B8%B0-11a188e17223)

  - 테스트 : $ ng test
  - 빌드 : $ ng build
  - e2e 테스트 : $ ng e2e
  - Webpack 설정 추출 : $ ng eject
  - 웹 문서 열기 : $ ng doc


TODO : Meteor 세팅




