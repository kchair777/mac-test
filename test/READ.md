# npm 구동하는방법 
1.  nvm --version 하면 1.1.11 확인nvm은Node.js여러버전을 설치해두고 
    편하게 관리해주는 도구 
1.  git --version 
1.  npm --version 하면 9.5.1 확인  
1.  brew install nvm 
1.  mkdir ~/.nvm
1.  npm init -y 하면 package.json화일생성됨  
1.  npm install parcel-bundler -D :
    (플래그는 개발용의존성패키지설치임)   
     나머지는 실제웹프라우져에서도 실행될수있다는 점이다. 
    node_modules 폴터 와 package-lock.json화일생성됨   
1.  npm install lodash 
1.   node_modules 폴터를 삭제후 다시, npm install하면  
      다시펙케지가 설치된다. 

1.  index.html과 main.js설치후 터미날차에서  
    parcel index.html실행한다.하니만 실행안되 
1.  "scripts": 이하 삭제함 
    "test": "echo \"Error: no test specified\" && exit 1"

1.  parcel index.html실행하면  

