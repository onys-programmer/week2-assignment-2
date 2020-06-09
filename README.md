# 간단 To-do 리스트 만들기

![todo mov](https://user-images.githubusercontent.com/14071105/83856356-5e55e380-a754-11ea-8330-ae466addda9e.gif)

간단한 To-do 리스트를 만들어주세요.

## 기능

* 사용자는 할 일을 입력할 수 있습니다.
* 사용자는 추가 버튼을 눌러서 할 일을 추가할 수 있습니다.
* 사용자는 할 일 목록을 볼 수 있습니다.
* 사용자는 완료 버튼을 눌러 할 일을 삭제할 수 있습니다.

## 제한 조건

* `if`는 사용할 수 있어도 `else` 사용하실 수 없습니다. `GuardClauses` 방법을 사용해주세요.
* `switch`는 사용하실 수 없습니다.
* `let`은 사용하실 수 없습니다. `const`만을 사용하여 문제를 해결해주세요.
* 함수 이름과 변수 이름에 줄임말은 사용하실 수 없습니다. 길더라도 명확하게 써주세요.
* indent(인덴트, 들여쓰기) depth를 1로 유지해주세요.
예를 들어, for문 안에 if문이 있으면 indent depth는 2입니다.
depth를 줄이는 좋은 방법은 함수(또는 메소드)를 분리하면 됩니다.

## 설치하기

```bash
npm install
```

## 실행하기

```bash
npm start
```

자동으로 브라우저가 켜지지는 않으니 브라우저에 `http://localhost:8080`을 입력하여 접속해 주세요.  

만약 현재 컴퓨터에서 이미 `8080`이라는 포트를 사용하고 있다면 `8081`으로 실행이 될 수도 있어요. 만약 `8081`도 사용하고 있으면 `8082`, `8083` ... 순서대로 찾아서 만들어집니다.

## 린트 실행하기

```bash
npm run lint
```

## 테스트 실행하기

```bash
npm test
```

## Todo List의 Todo List(?)
- [X] 화면에 '추가' 버튼 출력
- [X] '추가' 버튼 밑에 '아무것도 안하기'가 적힌 Todo List 렌더링
- [X] '추가' 버튼 클릭 시 아래에 '아무것도 안하기'라는 글자가 추가된다.
- [X] Todo 항목 별로 '완료' 버튼 렌더링
- [X] '완료' 버튼 클릭 시 Todo List에서 해당 항목 제거
- [X] '추가' 버튼 옆에 input 창 렌더링
- [X] '추가' 버튼 클릭 시 input 창 안의 내용이 Todo List에 추가됨
  - [X] 할일 추가 함수가 들어갈 내용을 입력받을 수 있도록 변경
  - [X] '추가' 버튼 클릭 시 input 창 초기화
