## Remote Repository 에서의 명령

github에서 Repository를 만들기

Git Bash → Local Repository

Github → Remote Repository (공유가능)

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/547f1c48-5a0b-472d-86a8-adaa5787ee36/6520c3da-7c76-4847-96fa-57852a5aa11b/image.png)

```java
//Local Repositry -> Remote Repository로 변경사항 업로드
git push

//Remote Repository -> Local Repository로 변경사항 적용
git pull

```

## 1. Working Directory

- 3번 기준 추가, 수정, 삭제 된 내용이 들어옴
- push 불가

## 2. Staging Area

★ commit 대상 목록 ★

★ git Hub 중 Commit 중요 ★

- push 후보

## 3. Git Directory

- 저장 완료, 현재 상태
- git remote와 연결되는 공간
- push, pull 가능
