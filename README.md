#README

### 1. 로컬 리포지토리 생성
	git init

### 2. 파일 추적 시작
	git add .

### 3. 파일 커밋
	git commit -m "first commit"

### 4. 브랜치 메인 변경
	git branch -m main

### 5. 원격 리포지토리 등록
	git remote add origin "HTTPS URL"

### 6. 푸시
	git push origin main
	git push <remote> <branch>

### 7. 풀
	git pull origin main
	git pull <remote> <branch>

### ETC
	README.md 파일 생성
	$ echo sampleText > README.md

	gitignore 파일 생성
	$copy con.gitignore
	 sampleText
	 ^z or ^c

### 주의사항
	.gitignore파일에 확장자 붙지 않도록 조심
	ex).gitignore.txt 