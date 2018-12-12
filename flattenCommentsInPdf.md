pdf 화일에 comment를 달거나, form을 만들고 그것을 다른 사람이 편집할 수 없도록, 혹은 인쇄할 때
항상 정확하게 인쇄되도록 pdf에 병합(flatten)해야 할 경우가 있다.

방법은 다음과 같다.

---

1. [UVSAR](https://www.uvsar.com/projects/acrobat/flattener/)에서 파일을 다운로드 받는다.

* [다운로드 링크](https://www.uvsar.com/projects/acrobat/flattener/acrobat-selective-flattener.zip)

2. 압축을 푼 후, 파일 `UVSAR_selectivFlatten.js`을 Acrobat JavaScript 폴더에 복사한다.

예) `C:\Program Files (x86)\Adobe\Acrobat DC\Acrobat\Javascripts`

3. Acrobat DC를 실행한 후, JavaScript를 실행할 수 있도록 설정을 변경한다.

편집 - 기본설정 - JavaScript - 
    JavaScript 
	[v] Acrobat JavaScript 사용 가능(J)
	
	JavaScript 보안
	[v] 메뉴 항목 JavaScript 실행 권한 활성화
	[v] 전역 개체 보안 정책 사용
	
---
	
* [참고 링크](https://forums.adobe.com/thread/2058398)
