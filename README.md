css내용중
float로 띄워져서 인식을 못할 때 해결방법 세가지
1. 부모태그에 overflow:hidden
2. 띄운 아래 태그에서 clear:both
3. 예) 띄운 태그 id가 aa일때 #aa:after{content:""; display:block; clear:both;}를 해준다 // 2번이랑 동일한 원리지만 바로 아래 태그에 공백을 주고 거기서 clear를 해주기 때문에 확실하게 할 수 있다.


github 원격저장소로 push하기위한 수정입니다.