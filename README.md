# CLI로 git hub에 올리기😊

***
*0. git bash 사용자 설정*
```bash
git config --global user.name "사용자이름"
git config --global user.email "사용자이메일"

#사용자 정보확인
git config --list
```

*1. git 초기화*
```bash
git init
```

*2. Git Hub에 Repository 생성*


*3. Git Hub에 올리기* 
```bash
#전체파일 올리기
git add .

#커밋 히스토리 남기기 
git commit -m "커밋메세지"

#생성된 Repository에 연결
git remote add origin (repository 주소)

#Git Hub에 올리기
git push origin (branch 이름)
```



