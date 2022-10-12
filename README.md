# Gateway

내부 서버들(포트)을 프록시로 연결시켜주는 앱입니다!

## 사용법

src/bind.json 파일 설정해주고

```json
{
  "(/이름)": (포트)
}
//여기서 이름이 index인것은 "/" 경로 포트에요!
```

인증서 경로 설정해주기!

.env

```
CERT_PATH=(cert 경로)
KEY_PATH=(key 경로)
```

설치 및 실행하기!

```bash
npm install

./run.sh
```

## 죽이기

```bash
./kill.sh
```
