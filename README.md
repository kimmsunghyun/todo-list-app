# 로컬 디렉토리 생성
mkdir todo-list-app
cd todo-list-app

# Git 초기화
git init

# GitHub 리포지토리 연결
git remote add origin https://github.com/your-username/todo-list-app.git

# 기본 파일 생성
echo "# Todo List App" > README.md
touch index.html app.js styles.css

# 변경 사항 커밋 및 푸시
git add .
git commit -m "Initial commit"
git push -u origin main
