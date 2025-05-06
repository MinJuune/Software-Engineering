1. Use Case : 회원가입

| Actor Action | System Response |
|--------------|-----------------|
| 1. 사용자가 ID, 비밀번호, 전화번호, 결제 수단, 선호 자전거 유형을 입력한다 | 2. 시스템이 입력된 정보를 저장하고 회원 가입을 완료했다는 메시지를 표시한다 |
|              |                 |
|              |                 |
|              |                 |

Extensions: 

2. Use Case : 로그인

| Actor Action | System Response |
|--------------|-----------------|
| 1. 사용자가 ID와 비밀번호를 입력한다 | 	2. 시스템이 사용자 정보를 확인하고 로그인에 성공하면 메인 페이지로 이동한다 |
|              |                 |
|              |                 |
|              |                 |

Extensions: 로그인 실패 시, 오류 메시지를 출력한다.

3. Use Case : 로그아웃

| Actor Action | System Response |
|--------------|-----------------|
| 1. 사용자가 로그아웃 버튼을 클릭한다 | 2. 시스템 접속을 종료한다 |
|              |                 |
|              |                 |
|              |                 |

Extensions:

4. Use Case : 회원 탈퇴

| Actor Action | System Response |
|--------------|-----------------|
| 1. 사용자가 회원 탈퇴를 요청한다 | 2. 시스템이 사용자에게 확인을 요청하고, 확인 시 계정과 관련된 모든 데이터를 삭제한다 |
|              |                 |
|              |                 |
|              |                 |

Extensions:

5. Use Case : 대여소 등록 

| Actor Action | System Response |
|--------------|-----------------|
| 1. 관리자가 대여소 이름, 위치(도시,주소), 보관 가능 수량, 운영 시간을 입력한다 | 2. 시스템이 대여소 정보를 저장하고 등록 완료 메시지를 출력한다 |
|              |                 |
|              |                 |
|              |                 |

Extensions:

6. Use Case : 대여소 목록 조회

| Actor Action | System Response |
|--------------|-----------------|
| 1. 관리자가 대여소 목록 조회를 요청한다 | 2. 시스템이 등록된 대여소 리스트를 출력한다 |
| 3. 관리자가 특정 대여소를 선택한다 | 4. ***시스템이 선택된 대여소의 상세 정보를 출력한다 |
|              |                 |
|              |                 |

Extensions: 
    a1. 관리자가 리스트에서 삭제 아이콘/버튼을 클릭한다
    a2. 시스템이 삭제 여부를 확인하고, 삭제 후 목록을 갱신한다

7. Use Case : 대여소 상세정보 확인

| Actor Action | System Response |
|--------------|-----------------|
| 1. 대여소 목록에서 특정 대여소을 선택한다 | 2. 시스템이 선택된 대여소의 상세 정보를 출력한다 |
|              |                 |
|              |                 |
|              |                 |

Extensions:

8. Use Case : 대여소 검색

| Actor Action | System Response |
|--------------|-----------------|
| 1. 사용자가 대여소 이름을 입력하여 검색한다 | 2. 시스템이 해당 이름과 일치하는 대여소 리스트를 출력한다 |
|              |                 |
|              |                 |
|              |                 |

Extensions:

9. Use Case

| Actor Action | System Response |
|--------------|-----------------|
|              |                 |
|              |                 |
|              |                 |
|              |                 |

Extensions:

10. Use Case

| Actor Action | System Response |
|--------------|-----------------|
|              |                 |
|              |                 |
|              |                 |
|              |                 |

Extensions:

11. Use Case : 자전거 등록

| Actor Action | System Response |
|--------------|-----------------|
| 1. 관리자가 자전거 정보를 입력 후 등록 버튼 클릭             | 2. 자전거 등록 완료 알림창 출력                |
|              |                 |
|              |                 |
|              |                 |

Extensions:   
None

12. Use Case : 자전거 리스트 조회

| Actor Action | System Response |
|--------------|-----------------|
| 1. None              |    2. 모든 등록된 자전거가 리스트로 출력             |
|              |                 |
|              |                 |
|              |                 |

Extensions:    
step 2 이후 관리자가 자전거 항목을 삭제할 수 있음  
step 2 이후 관리자가 자전거의 상태(사용가능 / 수리 중)를 수정할 수 있음

13. Use Case : 자전거 상세정보 조회

| Actor Action | System Response |
|--------------|-----------------|
| 1. 관리자가 등록된 자전거 리스트에서 원하는 자전거 클릭          |   2. 해당 자전거의 상세정보를 표시              |
|              |                 |
|              |                 |
|              |                 |

Extensions:   
None

14. Use Case : 자전거 즉시 대여

| Actor Action | System Response |
|--------------|-----------------|
|  1. 회원이 대여소 리스트에서 특정 대여소를 선택 후 클릭          |   2. 해당 대여소 상세정보 표시(대여소 이름, 위치, 사용 가능 자전거)              |
|  3. 사용 가능한 자전거 중 선택 후 즉시 대여 버튼 클릭            |   4. 즉시 대여 완료알림 표시              |
|              |                 |
|              |                 |

Extensions:   
step 2 이후 사용 가능한 자전거가 없을 시 회원이 예약대기를 신청할 수 있음

15. Use Case : 대여정보 조회

| Actor Action | System Response |
|--------------|-----------------|
| 1. None             | 2. 대여중인 자전거 리스트 및 정보 출력 |
|              |                 |
|              |                 |
|              |                 |

Extensions:   
None

16. Use Case

| Actor Action | System Response |
|--------------|-----------------|
|              |                 |
|              |                 |
|              |                 |
|              |                 |

Extensions:

17. Use Case

| Actor Action | System Response |
|--------------|-----------------|
|              |                 |
|              |                 |
|              |                 |
|              |                 |

Extensions:

18. Use Case

| Actor Action | System Response |
|--------------|-----------------|
|              |                 |
|              |                 |
|              |                 |
|              |                 |

Extensions:

19. Use Case

| Actor Action | System Response |
|--------------|-----------------|
|              |                 |
|              |                 |
|              |                 |
|              |                 |

Extensions:

20. Use Case

| Actor Action | System Response |
|--------------|-----------------|
|              |                 |
|              |                 |
|              |                 |
|              |                 |

Extensions:

21. Use Case

| Actor Action | System Response |
|--------------|-----------------|
|              |                 |
|              |                 |
|              |                 |
|              |                 |

Extensions:

22. Use Case

| Actor Action | System Response |
|--------------|-----------------|
|              |                 |
|              |                 |
|              |                 |
|              |                 |

Extensions:

23. Use Case

| Actor Action | System Response |
|--------------|-----------------|
|              |                 |
|              |                 |
|              |                 |
|              |                 |

Extensions:

24. Use Case

| Actor Action | System Response |
|--------------|-----------------|
|              |                 |
|              |                 |
|              |                 |
|              |                 |

Extensions:

25. Use Case

| Actor Action | System Response |
|--------------|-----------------|
|              |                 |
|              |                 |
|              |                 |
|              |                 |

Extensions:

26. Use Case

| Actor Action | System Response |
|--------------|-----------------|
|              |                 |
|              |                 |
|              |                 |
|              |                 |

Extensions:

27. Use Case

| Actor Action | System Response |
|--------------|-----------------|
|              |                 |
|              |                 |
|              |                 |
|              |                 |

Extensions:

28. Use Case

| Actor Action | System Response |
|--------------|-----------------|
|              |                 |
|              |                 |
|              |                 |
|              |                 |

Extensions:

29. Use Case

| Actor Action | System Response |
|--------------|-----------------|
|              |                 |
|              |                 |
|              |                 |
|              |                 |

Extensions:

30. Use Case

| Actor Action | System Response |
|--------------|-----------------|
|              |                 |
|              |                 |
|              |                 |
|              |                 |

Extensions:

31. Use Case

| Actor Action | System Response |
|--------------|-----------------|
|              |                 |
|              |                 |
|              |                 |
|              |                 |

Extensions:

32. Use Case

| Actor Action | System Response |
|--------------|-----------------|
|              |                 |
|              |                 |
|              |                 |
|              |                 |

Extensions:

33. Use Case

| Actor Action | System Response |
|--------------|-----------------|
|              |                 |
|              |                 |
|              |                 |
|              |                 |

Extensions:

34. Use Case

| Actor Action | System Response |
|--------------|-----------------|
|              |                 |
|              |                 |
|              |                 |
|              |                 |

Extensions:

35. Use Case

| Actor Action | System Response |
|--------------|-----------------|
|              |                 |
|              |                 |
|              |                 |
|              |                 |

Extensions:

36. Use Case

| Actor Action | System Response |
|--------------|-----------------|
|              |                 |
|              |                 |
|              |                 |
|              |                 |

Extensions:

37. Use Case

| Actor Action | System Response |
|--------------|-----------------|
|              |                 |
|              |                 |
|              |                 |
|              |                 |

Extensions:

38. Use Case

| Actor Action | System Response |
|--------------|-----------------|
|              |                 |
|              |                 |
|              |                 |
|              |                 |

Extensions:

39. Use Case

| Actor Action | System Response |
|--------------|-----------------|
|              |                 |
|              |                 |
|              |                 |
|              |                 |

Extensions:

40. Use Case

| Actor Action | System Response |
|--------------|-----------------|
|              |                 |
|              |                 |
|              |                 |
|              |                 |

Extensions:
