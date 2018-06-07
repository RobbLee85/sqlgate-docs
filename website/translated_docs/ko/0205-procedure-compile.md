---
id: 0205-procedure-compile
title: 프로시저 실행 및 컴파일
sidebar_label: 프로시저 실행 및 컴파일
---


## 코드 자동 완성 기능을 이용하여 코드 입력 줄이기

코드 자동 완성 기능을 이용하여 코드 입력 줄이기를 설명합니다.

1. 데이터베이스에 접속합니다.
2. 주 메뉴 파일>새로 만들기>PL/SQL 편집기를 실행합니다. 또는 새로 만들기 도구 모음에서 PL/SQL 편집기를 클릭합니다.
3. 프로시저를 작성합니다.
4. PL/SQL 편집기에서 변수, 매개변수로 선언된 값들은 자동으로 나타납니다.
5. 원하는 변수나 매개변수를 커서로 선택 하거나 더블 클릭합니다.
6. 실행 결과를 확인합니다.

![코드 자동 완성 기능](https://s3.ap-northeast-2.amazonaws.com/sqlgate-manual-content/B921C3538F4C965F2F1380D1F4696857.jpg)

> 노트 : 네이게이터는 런타임 코드를 분석하여 매개 변수, 변수, 코드를 트리 구조로 보여줍니다.



## 프로시저의 오류를 찾아서 컴파일 하기

프로시저의 오류를 찾아서 컴파일 하기를 설명합니다.

1. 데이터베이스에 접속합니다.
2. 주 메뉴 파일>새로 만들기>PL/SQL 편집기를 실행합니다. 또는 새로 만들기 도구 모음에서 PL/SQL 편집기를 클릭합니다.
3. 프로시저를 작성합니다.
4. 주 메뉴 쿼리>실행을 실행합니다. 또는 실행 버튼을 클릭하거나 F5를 누릅니다.
5. 오류가 있으면 오류 탭에 나타나고 편집기는 해당 줄을 표시합니다.

![프로시저 오류 찾아서 컴파일 하기](https://s3.ap-northeast-2.amazonaws.com/sqlgate-manual-content/E8E787DC5BAB59ACB13F0C5AB62C01AD.jpg)

6. 오류를 확인하고 오류를 수정합니다.
7. 실행 버튼을 클릭하거나 F5를 누릅니다.
8. 상태 막대에서 프로시저가 생성되었습니다.를 확인합니다.



## 프로시저 실행하여 결과 값 확인하기

프로시저 실행하여 결과값 확인하기를 설명합니다.

1. 데이터베이스에 접속합니다.
2. 주 메뉴 파일>새로 만들기>PL/SQL 편집기를 실행합니다. 또는 새로 만들기 도구 모음에서 PL/SQL 편집기를 클릭합니다.
3. 프로시저를 작성합니다.

![프로시저 작성](https://s3.ap-northeast-2.amazonaws.com/sqlgate-manual-content/2EF9876F89B86245DCB3C01B860A30B8.jpg)

4. 주 메뉴 쿼리>실행을 실행하여 컴파일 합니다. 또는 도구 모음에서 실행 버튼을 클릭하거나 F5를 누릅니다.
5. 정상 컴파일 된 메세지 확인 후, 프로시저 실행 버튼을 클릭하여 프로시저를 실행 합니다.

![프로시저 컴파일 후 실행](https://s3.ap-northeast-2.amazonaws.com/sqlgate-manual-content/560AF209EF88DD824B74ECD43014733A.jpg)

6. 파라미터 값을 입력 하고 , SQL 실행 버튼을 클릭하거나, F5를 누릅니다.

![프로시저 실행 후 파라미터 값 입력](https://s3.ap-northeast-2.amazonaws.com/sqlgate-manual-content/BA30B22D2DFEDD6935FEC62487BBE353.jpg)

7. SQL DBMS OUTPUT 탭에서 실행 결과를 확인합니다.

![IMAGE](https://s3.ap-northeast-2.amazonaws.com/sqlgate-manual-content/DB494295EA66D5E92B404D70ED835A0D.jpg)[DBMS_OUTPUT 결과 확인]


## 프로시저 코딩하면서 버전 기록 보기

프로시저 코딩하면서 버전 기록 보기를 설명합니다.

1. 데이터베이스에 접속합니다.
2. 주 메뉴 파일>새로 만들기>PL/SQL 편집기를 실행합니다. 또는 새로 만들기 도구 모음에서 PL/SQL 편집기를 클릭합니다.
3. 프로시저를 작성합니다.
4. 주 메뉴 보기>SQL 기록을 실행합니다. 또는 도구 모음에서 SQL 기록 버튼을 클릭하거나 F8을 누릅니다.
5. Procedure/Function을 클릭합니다.
6. 버전 기록을 클릭하면 프로시저의 내용이 나타납니다. 더블 클릭하거나 Ctrl+Enter를 누르면 편집기에 추가가 됩니다.

![버전 기록 보기](https://s3.ap-northeast-2.amazonaws.com/sqlgate-manual-content/4AB2A77BDE41CD2B82656B4555F0DC8A.jpg)


## 오류가 난 프로시저 확인하기

오류가 난 프로시저 확인하기를 설명합니다.

1. 데이터베이스에 접속합니다.
2. 주 메뉴 보기>개체 탐색기를 실행합니다.
3. 프로시저 개체를 클릭합니다.
4. 오류가 난 프로시저를 확인합니다.

![오류가 난 프로시저 확인](https://s3.ap-northeast-2.amazonaws.com/sqlgate-manual-content/4718C54091BA0F0F9FD5CC57BB655A62.jpg)


## 오류가 난 프로시저 디버깅 및 재컴파일 하기

오류가 난 프로시저 디버깅 및 재컴파일 하기를 설명합니다.

1. 데이터베이스에 접속합니다.
2. 주 메뉴 보기>개체 탐색기를 실행합니다.
3. 프로시저 개체를 클릭합니다.
4. 오류가 난 프로시저 개체에서 마우스 오른쪽 클릭하고 수정을 선택 합니다.
5. PL/SQL 편집기가 실행 됩니다. 오류를 수정합니다.

![오류가 난 프로시저 오류 수정](https://s3.ap-northeast-2.amazonaws.com/sqlgate-manual-content/4718C54091BA0F0F9FD5CC57BB655A62.jpg)

6. 주 메뉴 도구>개체 재컴파일을 실행합니다. 또는 도구 모음에서 개체 재컴파일을 클릭합니다.

![개체 재컴파일 선택](https://s3.ap-northeast-2.amazonaws.com/sqlgate-manual-content/12060563A79FCA475E1FE621105678D3.jpg)

7. 스키마와 프로시저를 선택하고 검색을 클릭합니다.
8. 재컴파일 할 프로시저 개체를 선택하고 컴파일 버튼을 클릭합니다

![개체 재컴파일 실행](https://s3.ap-northeast-2.amazonaws.com/sqlgate-manual-content/43589961670C31AC576D6DD1F7AB767E.jpg)

9. 선택한 PROCEDURE를 컴파일하시겠습니까? 창을 확인합니다. 예를 클릭합니다.
10. 실행 결과를 확인합니다.

![개체 재컴파일 실행 결과 확인](https://s3.ap-northeast-2.amazonaws.com/sqlgate-manual-content/310B7CCB52D883CF099FCE3E7B3F6F7D.jpg)

