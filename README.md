<img src="https://user-images.githubusercontent.com/78431728/202333442-ba9ffbbe-e579-4c29-b1f2-436b60a8df95.png" width="90%">


## 👟🏃 RUNDAY_SERVER 👟🏃

> 31th IN SOPT 합동세미나 5조 <br>
> 프로젝트 기간 : 2022.11.12 ~ 2022.11.26

<br>

### <strong> 🏃 Server 🏃 </strong>

| <img src="https://avatars.githubusercontent.com/u/82046935?v=4" width="200">|<img src="https://user-images.githubusercontent.com/58043306/178588958-53a24567-3815-49af-84c7-1faadb74166b.jpg" width="200">|
| :-----------------------------------: | :-----------------------------------------------: |
|                김민욱                 |                      한유진                       |
| [ 🐸 coreminw ](https://github.com/coreminw) | [ 🐸 yujindonut ](https://github.com/yujindonut) |

<br>

### <strong> 🏃 Used 🏃 </strong>
<br>
<p>
<img alt="TypeScript" src="https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white"/>
<img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-4169E1.svg?style=for-the-badge&logo=postgresql&logoColor=white"/>
<img alt="Prisma" src="https://img.shields.io/badge/Prisma-2D3748.svg?style=for-the-badge&logo=Prisma&logoColor=white"/>
<img alt="AWS" src="https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white"/><br>
<img alt="Prettier" src="https://img.shields.io/badge/Prettier-F7B93E.svg?style=for-the-badge&logo=Prettier&logoColor=black"/>
<img alt="ESLint" src="https://img.shields.io/badge/ESLint-4B32C3.svg?style=for-the-badge&logo=ESLint&logoColor=white"/>
</p>
  
<br>

## 🏃 Coding Convention 🏃
<br>
<details markdown="1">
<summary>네이밍</summary>

### DB

- DB 이름은 **UpperCamelCase**를 사용합니다.

<br>

### 함수, 변수, 타입
- 함수와 변수에는 **lowerCamelCase**를 사용합니다.
- 함수명은 동사로 시작합니다.
- 타입명은 **파스칼케이스**를 사용합니다.
  - interface이름에 I를 붙이지 않습니다.
- 기본 클래스 파일을 생성하거나 컴포넌트를 생성할 때는 약어 규칙에 따라 네이밍합니다.  

<br>

### 변수 네이밍

- `사진` → photo
- `유저` → user 
- `배열을 담은 변수`→ ~s(복수형)
- `상태` → status 

---
</details>

<br>

## ✉️ Commit Convention

```
[CHORE] 코드 수정, 내부 파일 수정 
[FEAT] 새로운 기능 구현 
[ADD] Feat 이외의 부수적인 코드 추가, 라이브러리 추가, 새로운 파일 생성 시, 에셋 추가
[HOTFIX] issue나, QA에서 급한 버그 수정에 사용
[FIX] 버그, 오류 해결
[REMOVE] 쓸모없는 코드 삭제 
[DOCS] README나 WIKI 등의 문서 개정
[MOVE] 프로젝트 내 파일이나 코드의 이동 
[RENAME] 파일 이름, 변수명, 함수명 변경이 있을 때 사용합니다. 
[REFACTOR] 전면 수정이 있을 때 사용합니다 
```
<br>

## ✨ Github Management
<br>

<details>
<summary> ✨ Gitflow ✨ </summary>
<div markdown="1">  

```
1. Issue를 생성한다.
2. 깃 컨벤션에 맞게 Branch를 생성한다.
3. Add - Commit - Push - Pull Request 의 과정을 거친다.
4. Pull Request가 작성되면 작성자 이외의 다른 팀원이 Code Review를 한다.
5. Code Review가 완료되면 Pull Request 작성자가 develop Branch로 merge 한다.
6. merge된 Branch는 삭제한다.
7. 종료된 Issue와 Pull Request의 Label과 Project를 관리한다.
```
	
### 🌴 브랜치
---
#### 📌 브랜치 단위
- 브랜치 단위 = 이슈 단위 = PR단위

#### 📌 브랜치명
- 브랜치는 뷰 단위로 생성합니다.
- 브랜치 규칙 → feature/#이슈번호-탭-기능간략설명
- `ex) feature/#1-postLike`
- 탭이름 - Run, MyPage
- 공통적인 것 작업 - Global
    - feature/chore/fix/network

<br>
	
### 💡 이슈, PR 규칙
---
	
#### 📌 Issue명 = PR명
- [FEAT] - 기능 구현
- [FIX] - 버그 수정
- [REFACTOR] - 코드 리팩토링(결과물은 같지만 코드의 향상)
- [CHORE] - 수정
- [ADD] - 세팅 및 라이브러리 추가

</details>

<br>

### <strong> 🏃 APIs 🏃 </strong>
|   EndPoint   |               detail               | developer | done |
| :------: | :--------------------------------: | :-------: |:--: |
|   User  |       마이페이지 정보 조회       |   유진    |  ✅  |
|         |       유저 달리기 정보       |   민욱    |  ✅  |
|   Run   |       좋아요 누르기       |   민욱    |  ✅  |
|         |       좋아요 취소       |   유진    |  ✅  |

<br>

### <strong> Dependencies</strong>
```
  
```

<br>

## <strong> ERD & Directory Tree</strong>
<details>
<summary>🗄 ERD</summary>

![image](https://user-images.githubusercontent.com/78431728/202331284-12894f7d-81c4-40f1-92cd-c0afe4aaa63a.png)

</details>
<br>
<details>
<summary>📦 Directory Tree</summary>

```bash

```
</details>
<br>
