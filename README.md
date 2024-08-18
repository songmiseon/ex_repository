### 설정
```(url)
git config --global user.name '아이디'
git config --global user.email '메일주소'
```
* ex)<br>
git config --global user.name 'songmiseon'<br>
git config --global user.email 'sms5514@hanmail.net'

### 설정 확인
```
git config --list
```

### git 초기화(1회 수행)
```
git init
```

### 변경된 파일 올리기
```
git add .
git add 파일명
```
* .(모든 파일)
* 특정 파일만 선택

### 상태 확인(추가 인식 파일 확인)
```
git status
```

### 히스토리 생성
```
git commit -m "first commit"
```
* ex) 과제최종, 과제최종의 최종

### 프로젝트와 github 연결 설정(1회 수행)
```
git remote add origin repository주소
```
* 예) git remote add origin https://github.com/songmiseon/ex_project.git

### 연결 확인
```
git remote -v
```

### 파일 올리기
```
git push -u origin master
```

### 내용 수정시 진행 사항
```
히스토리 생성 > 파일 올리기
```