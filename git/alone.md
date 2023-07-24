# 개인 복습

```shell
github cycle
```

- 무언가 소스코드를 변경하게 되면 > 저장 > git add . > git commit -m "내용" > push



- 최초
git init > git add . > git commit -m 'message' > git remote add origin <remote url> > git push origin master



## 기본 명령어

```shell
git init
```
- `.git directory`를 생성하는 명령어

```shell
git add.
```
- `working directory`에 있는 파일, 폴더를 `staging area`에 추가
- add 하기 전에 파일이 저장이 되었는지 확인하기

```shell
git commit -m 'message'
```
- `staging area`에 올라간 파일들을 저장

```shell
git remote add origin <remote url>
```
- 원격저장소 주소를 `origin`이라는 별명으로 저장

```shell
git push origin master
```
- `master` 브랜치를 `origin` 원격저장소로 업로드