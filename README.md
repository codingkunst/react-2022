# React
### 설치
- `yarn create react-app .`

### 수정
- `./src/index.js` - **입구 파일** 
- 전역적인 **설정**들이 들어감

### 배포
- `npm run build`
  - `build` 폴더 생성됨
- `npx serve -s build`
  - 사용자가 어떤 경로로 들어오곤 간에 `build` 폴더 안에 `index.html` 파일을 서비스 해줌

### 컴포넌트
- 사용자 정의 태그
- **함수**로 정의하면 된다
- 반드시 첫 글자를 **대문자**로 시작해야함 

### props
- 컴포넌트의 속성

### 이벤트
- `<input type="button" onclick="alert('hi')">`
- `event.preventDefault();` - 기본 동작을 방지, 리로드x
- `event.target` - **target**은 이벤트를 유발시킨 태그를 가리킴

### state
- [ Prop → state → return ]
- prop과 함께 컴포넌트 함수를 다시 실행해서 새로운 return 값을 만들어주는 데이터
  - `prop` - 컴포넌트를 사용하는 외부자를 위한 데이터
  - `sate` - 컴포넌트를 만드는 내부자를 위한 데이터

## 대부분의 애플리케이션은 CREATE(생성) READ(읽기) UPDATE(수정) DELETE(삭제) 4가지 기능을 가지고 있다
### Create


### Update


### Delete

