## 1장. 자바스크립트 소개

자바스크립트는 *웹*의 프로그래밍 언어이다. 데스크톱,태블릿,스마트폰 등에서 동작하는 최신 웹 브라우저는 모두 자바스크립트 인터프리터를 내장하고 있다.

이에 힘입어 자바스크립트는 역사상 가장 널리 퍼진 프로그래밍 언어가 되었다.

---

자바스크립트는 _객체 지향_, _함수형 프로그래밍_ 스타일에 적합한 고수준의 동적인 인터프리터 언어라는 사실을 아는 것은 도움될 것이다.

---

_자바스크립트 변수에는 타입이 없다._ 이런 문법은 어느정도 자바(Java)에서 차용한 것이 맞지만, 이를 제외하고는 둘의 연관성은 거의 없다.

---

자바스크립트는 웹 초기에 넷스케이프(현 모질라)에서 사용하는 언어를 위해 선 마이크로시스템즈(현 오라클)에서 등록한 상표이다.
넷스케이프는 이 언어를 표준화하기 위해 ECMA에 제출했으며, 상표권 문제 때문에 표준화된 언어는 _'ECMAScript'_ 라는 이름과 그 약어 *'ES'*를 가게 되었다.

2015년에 발표한 *ES6*는 *클래스*와 _모듈_ 문법을 포함해 새 중요한 기능을 도입하였고, 이를 계기로 스크립트 언어에서 대규모 소프트웨어에도 적합한 범용 언어가 되었다.

언어가 발전함에 따라 초기(ES5 전) 버전의 결함을 수정하려고 했으나 _하위 호환성 유지 문제_ 때문에 결함이 심각하더라도 제거할 수 없는 구식 기능이 여전히 남아있다.

ES5 이후 버전에서는 초기 버전의 실수를 대부분 해결한 *스트릭트 모드*를 사용할 수 있다.

---

자바스크립트 코어에는 숫자, 텍스트, 배열, 세트, 맵 등을 다루는 최소한의 API가 정의되어 있지만 입출력에 관한 부분은 정의되어 있지 않다.

---

입출력, 네트워크, 스토리지, 그리고 그래픽 같은 좀 더 발전된 기능은 자바스크립트가 임베드된 '호스트 환경'이 담당한다.

본래 자바스크립트의 호스트 환경은 '웹 브라우저'였으며 현재도 이가 대부분이다.

그러나 2010년에 자바스크립트 코드에 다른 호스트 환경이 등장하였는데. 이가 바로 *'노드(Node)'*이다.

웹 브라우저 API를 벗어나 운영 체제 전체에 접근해 파일을 읽고 쓰고, 네트워크를 통해 데이터를 송수신하고, HTTP 요청을 보내고 받을 수 있게 되었다. 웹 서버뿐만 아니라
셸 스크립트를 대체하는 단순한 유틸리티 스크립트를 만들 때도 편리하게 사용할 수 있다.