# 예제로 익히는 HTML5/CSS3

## Git 버전 관리

본인의 github에 **HTML_Basic 저장소 생성**한 후 저장소 주소 복사

```bash
https://www.github.com/{Github ID}/HTML_Basic.git
```

### git clone

```bash
# .git 디렉토리를 포함해서 clone
git clone https://www.github.com/seulbinim/webcafeHTML5.git

# remote 저장소 조회
git remote -v

# remote 저장소 삭제
git remote rm origin

# remote 저장소 등록
git remote add https://www.github.com/{Github ID}/HTML_Basic.git

# remote 저장소로 백업
git push origin main
```

### npx degit

```bash
# git 버전 관리 history 제외하고 Clone
npx degit seulbinim/webcafeHTML5 HTML_Basic

# git 버전 관리를 위한 초기화
git init

# 최초 커밋 (Commit)
git add .
git commit -m "초기화 및 백업(Initialization & Backup)"

# 리모트(Remote) 저장소 등록
git remote add origin https://www.github.com/{Github ID}/HTML_Basic.git

# 리모트(Remote) 저장소로 백업
git push origin main
```
