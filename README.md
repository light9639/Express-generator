# :zap: Express-generator 기본 템플릿.

![localhost_3000_](https://user-images.githubusercontent.com/95972251/204212320-f784f25b-8bbd-4a0f-a96b-f747074c482c.png)

:sparkles: Express-generator 기본 템플릿입니다. :sparkles:
## :tada: Express-generator 설치하기
- npm, yarn을 이용하여 설치하려면 
```bash
npm i -g express-generator(npm i 대신 install도 가능함.)
```

- 전역 설치 후 터미널에 다음과 같이 입력한다.
```bash
express my-app --view=pug
```

## :white_check_mark: 추가 설치
- 폴더로 이동 후 npm, yarn 설치
```bash
cd my-app
```

```bash
npm install

or

yarn
```

- 설치 이후 localhost 포트 번호를 설정하려면 /bin/www.js로 이동 후 포트번호를 설정하면 됨.
```bash
var port = normalizePort(process.env.PORT || '3000');
app.set('port', port);
```

- 설정 이후 `npm run start` 또는 `yarn start` 입력 후. 해당 포트를 기준으로 localhost:3000으로 접속하면 됩니다.

## 📎 출처
- https://expressjs.com/en/starter/generator.html 문서를 토대로 작성하였습니다.
