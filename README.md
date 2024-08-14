# Git 관련

## 설치여부 확인

```bash
git version
```

## 설치방법(Mac OS 또는 Windows)

- [보러가기](https://github.com/git-guides/install-git)

## Repository 생성

- git init 현재 디렉토리를 Git 저장소로 변환
- --initial-branch=main 초기 Branch 이름
```bash
git init --initial-branch=main
```
- 현재 디렉토리의 모든 변경 사항을 commit 할 준비상태(Stage)로 만든다
```bash
git add .
```
- Git에서 버전 관리를 위한 스냅샷.특정 시점의 코드 상태를 기록
```bash
git commit -m "initial commit"
```
- Commit 기록을 보여준다
```bash
git log
```
- 원격 저장소(remote repository) 추가
```bash
git remote add origin [여러분의 repository 주소]
```
- 원격 저장소(remote repository) 확인
```bash
git remote -v
```
- 원격 저장소로 commit된 변경 사항 업로드
```bash
git push origin main
```
