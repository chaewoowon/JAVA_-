# To-Do List Manager

## 1. 개요
### 1.1 목적
이 프로그램은 사용자가 할 일을 효율적으로 관리할 수 있도록 지원합니다. 작업을 추가, 삭제, 조회하고, 파일로 저장하거나 불러올 수 있는 기능을 제공합니다.

### 1.2 대상
- 작업 목록을 체계적으로 관리하고 싶은 사용자
- 파일 입출력을 배우거나 활용하고 싶은 Java 학습자

---

## 2. 프로그램의 중요성 및 필요성
### 2.1 중요성
- 일정을 효율적으로 관리하여 작업을 체계적으로 수행할 수 있습니다.
- 파일 입출력 및 컬렉션 프레임워크의 활용 사례를 학습할 수 있습니다.

### 2.2 필요성
- Java 프로그래밍 기초를 학습하고 응용하기 위한 실습 예제입니다.
- 간단한 사용자 인터페이스로 할 일 목록을 관리하는 프로그램의 필요를 충족합니다.

---

## 3. 프로그램 수행 절차
### 3.1 다이어그램
- 프로그램의 전체 절차는 다음과 같습니다:
  1. 사용자 메뉴를 출력합니다.
  2. 사용자는 메뉴에서 작업을 선택합니다.
  3. 선택한 작업에 따라 작업 목록을 관리하거나 파일로 저장/불러옵니다.

---


### 3.2 클래스 다이어그램
- 클래스: `ToDoListManager`
- 주요 메서드:
- `작업 추가(String task)`: 작업 추가
- `작업 삭제(int index)`: 작업 제거
- `작업 보기()`: 현재 작업 목록 보기
- `작업 저장(String filename)`: 작업 목록 파일 저장
- `작업 불러오기(String filename)`: 작업 목록 파일 불러오기

클래스 다이어그램 : https://drive.google.com/file/d/16qn3YFqtpReGBIvsrmBWUi_Utc_Zyu7c/view?usp=drive_link

### 3.3 절차 설명
1. 작업 추가 : 사용자는 작업을 입력하여 목록에 추가합니다.
2. 작업 삭제 : 작업 번호를 입력하여 목록에서 삭제합니다.
3. 작업 보기 : 현재 작업 목록을 출력합니다.
4. 작업 저장 : 작업 목록을 파일에 저장합니다.
5. 작업 불러오기 : 저장된 파일에서 작업 목록을 불러옵니다.
6. 프로그램 종료 : 프로그램을 종료합니다.

---

## 4. 느낀점
이 프로그램 개발을 통해 다음을 배울 수 있어 흥미로운 시간이었습니다.
- Java의 컬렉션 프레임워크(ArrayList, HashSet) 활용법
- 파일 입출력(BufferedReader, BufferedWriter)의 기초
- 예외 처리 및 사용자 입력 검증의 중요성
- 다이어그램 작성 및 설계의 체계적 접근 방법
