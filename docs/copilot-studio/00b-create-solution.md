# 실습 환경 설정

## 학습 목표
- 실습 환경 설정

## 시나리오
- 실습에서 만들게 되는 각종 자산들을 묶어서 관리하기 위해 솔루션을 만든다.
- 실습을 위한 OneDrive 폴더 구조를 설정한다.

## 지시사항

1. `https://copilotstudio.microsoft.com/`로 이동한다. `...` 버튼을 클릭하여 `솔루션` 메뉴로 이동한다. 
![](../../imgs/00b-create-solution/01.PNG)

2. `새 솔루션`을 클릭한 뒤 `표시 이름`을 `Copilot Studio training[본인영문명 또는 이니셜]`으로 설정한다 (중복 방지). `이름`은 자동으로 채워지는 것을 확인할 수 있다. `새 게시자`를 클릭한다.
![](../../imgs/00b-create-solution/02.PNG)

3. `표시 이름`과 `이름`을 본인의 영문 성함으로 입력한다. `접두사`에는 본인의 이니셜을 입력한다. `저장`을 클릭한다. 
![](../../imgs/00b-create-solution/03.PNG)

```{Note}
게시자를 설정함으로써 해당 솔루션과 솔루션 내 자산(asset)들을 누가 만들었는지 IT에서 관리가 가능하다. 
```

4. 새로 만든 게시자를 `게시자` 메뉴에서 선택한다. `선호하는 솔루션으로 설정` 체크박스를 선택한다. 그리고 `만들기`를 클릭한다.
![](../../imgs/00b-create-solution/04.PNG)

```{Note}
선호하는 솔루션으로 설정해두면 추후 개발하는 모든 에이전트들이 기본값(default)으로 해당 솔루션 내에 저장된다. 에이전트를 만드는 시점에서 해당 에이전트가 다른 솔루션 내에 저장되게 설정할 수도 있다.
```

5. `신규 > 자세히 > 연결 참조`를 클릭한다. 
![](../../imgs/00b-create-solution/05.PNG)

6. `표시 이름`을 `Excel`로 설정한다. `커넥터`란에 `Excel Online(Business)`를 입력하여 선택한다. `새 연결`을 클릭한다.
![](../../imgs/00b-create-solution/06.PNG)

```{Note}
본인의 M365 환경 상에 있는 Excel 파일에 접근하기 위해 사용자 인증 정보를 활용하여 연결 설정을 해줘야 한다.
```

7. `만들기`를 클릭한다.
![](../../imgs/00b-create-solution/07.PNG)

8. 로그인 되어 있는 본인의 인증 정보를 클릭한다.
![](../../imgs/00b-create-solution/08.PNG)

9. 연결이 만들어 진 것을 확인할 수 있다.
![](../../imgs/00b-create-solution/09.PNG)

10. 솔루션 페이지로 이동하여 `새로 고침`을 클릭한다. `연결` 메뉴에 앞서 만든 연결 정보가 표시되는 것을 확인할 수 있으며, 해당 연결 정보를 클릭한다. 연결한 본인의 이메일이 나와 있다.
![](../../imgs/00b-create-solution/10.PNG)

11. `만들기`를 클릭한다.
![](../../imgs/00b-create-solution/11.PNG)

12.  5번 부터 11번 과정을 반복하여 Teams, OneDrive, Outlook 커넥터를 추가한다. 추가할 때 `표시 이름`과 `커넥터`는 아래 정보를 활용한다. 완료가 되면 총 4개의 커넥터가 표시된다.
- `표시 이름`: `Teams` / `OneDrive` / `Outlook`
- `커넥터`: `Microsoft Teams` / `비즈니스용 OneDrive` / `Office 365 Outlook`
![](../../imgs/00b-create-solution/12.PNG)

13. `https://m365copilot.com/`으로 이동한다. `앱` 메뉴를 클릭한뒤 `OneDrive`로 이동한다.
![](../../imgs/00b-create-solution/13.PNG)

14. `내 파일`로 이동한다.
![](../../imgs/00b-create-solution/14.PNG)

15. `만들기 또는 업로드 > 폴더`를 클릭한다.
![](../../imgs/00b-create-solution/15.PNG)

16. `코파일럿 에이전트 교육 개인 폴더`를 폴더명으로 입력한뒤 `만들기`를 클릭한다.
![](../../imgs/00b-create-solution/16.PNG)

17. `코파일럿 에이전트 교육 개인 폴더` 폴더 내로 이동한 뒤 `만들기 또는 업로드 > 폴더` 기능을 활용하여 `프로젝트2`, `프로젝트3` 폴더를 생성한다.
![](../../imgs/00b-create-solution/17.PNG)

18. 실습 데이터가 존재하는 쉐어포인트 사이트로 이동하여 `일반 > 프로젝트2` 폴더로 이동한다. `휴가 종합표.xlsx`를 선택한 뒤 `... > 다음으로 복사` 메뉴를 클릭한다.
![](../../imgs/00b-create-solution/18.PNG)

19. `내 파일 > 코파일럿 에이전트 교육 개인 폴더 > 프로젝트2`로 이동한뒤 `여기에 복사`를 클릭한다.
![](../../imgs/00b-create-solution/19.PNG)

20. 쉐어포인트 문서에서 `일반 > 프로젝트3`으로 이동한 뒤 `견적서`와 `템플릿` 폴더를 동시 선택한다. `... > 다음으로 복사`를 클릭한다.
![](../../imgs/00b-create-solution/20.PNG)

21. `내 파일 > 코파일럿 에이전트 교육 개인 폴더 > 프로젝트3`로 이동한뒤 `여기에 복사`를 클릭한다.
![](../../imgs/00b-create-solution/21.PNG)

## 참고 문헌
- https://github.com/microsoft/mcs-labs/tree/main/labs/setup-for-success