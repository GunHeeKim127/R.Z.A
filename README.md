##오늘한 일

###8월29일

>1.환경설정(개발환경)
> ㄴ git 및 mongoDB 덜함-내일 마저 진행
> ㄴ node.js express 연동 완료

>2. 페이지 정의

>3. class 정의

###8월 30일

>1.환경설정(개발환경)
> ㄴ git 재설정
> ㄴ mongoDB재설정

>2.html기능구축 코딩

>3.express설치
> npm install express -save

 ```javascript
const express = require('express'); 
const app = express();
const port = 3000;

app.get('/', (req, res)=>res.send('Hello World'));
app.listen(port,() => console.log(`listen port ${port}`));
```
>4.pakage.json 수정
>npm run start 되게하기

```json
{
  "name": "login-study02",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "scripts": {
    "start": "node index.js",
    "test":"echo\"Error: no test specified\" && exit 1"
  },
  "author": "",
  "license": "ISC",
  "dependencies": {
    "express": "^4.18.1" 
  }
}
```

![image](https://user-images.githubusercontent.com/53036090/187440197-b8e50a3e-b183-443b-b0b6-03e65a011571.png)
