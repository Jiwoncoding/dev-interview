## HTML CSS 면접 질문

### Cascading에 관해서 설명해주세요  
계단모양의 폭포를 의미하며 CSS에서 스타일 시트의 우선순위를 지정하는 방식이 폭포수와 닮아 붙여진 의미이다.  

### CSS 애니메이션과 JS애니메이션의 차이에 대해 설명해주세요  
간단하게 처리하는 애니메이션의 경우 CSS로 처리하고, 복잡하고 무거운 애니메이션은 JS로 처리한다. JS애니메이션을 사용하면 브라우저 호환성이 좋다.  

### Position 속성을 나열해주세요  
static, relative, absolute, fixed, sticky    

### Position을 어떻게 사용하는지 알려주세요  
static은 position의 default 값으로 요소들이 HTML에 작성된 순서대로 배친된다. relative는 요소를 원래 위치를 기준으로 상대적으로 배치해준다. absolute는 부모 요소를 기준으로 top, left, right, bottom 속성을 적용한다. fixed는 화면에 고정시킬 때 사용하고, sticky는 화면을 스크롤링할 때 효과가 나타난다.  

### DOCTYPE
Document Type의 약자로 HTML이 어떤 버전으로 작성되었는지 미리 선언하여 웹 브라우저가 내용을 올바로 표시할 수 있도록 한다.

### 표준모드와 호환모드
브라우저는 HTML 문서가 DOCTYPE을 가지고 있지 않으면 호환 모드로 렌더링하고, 가지고 있다면 주어진 DOCTYPE에 맞게 표준 모드로 렌더링한다.

### data-속성
DOM에 데이터를 저장할 수 있는 사용자 정의 데이터 속성. data-다음 오는 값이 데이터가 된다.

### local storage vs session storage vs cookie
- local storage: 생성자는 클라이언트, 서버. 지속시간은 설정 여부에 따르고 서버 통신 가능
- session storage: 생성자는 클라이언트. 지속시간은 명시적으로 지울 때까지이고 서버 통신 불가능
- cookie: 생성자는 클라이언트. 지속시간은 윈도우를 닫을 때까지. 서버 통신 불가능

### script vs script async vs script defer
- script: HTML 파싱이 중단되고 즉시 로드, 로드된 스크립트가 실행되고 파싱이 재개
- script async: HTML 파싱과 병렬적으로 로드. 스크립트를 실행할 때는 파싱 중단. 
- script defer: HTML 파싱과 병렬적으로 로드. 파싱이 끝나고 스크립트를 로드
- script async와 script defer는 src속성이 없으면 적용되지 않는다.
