# 설치 및 실행 가이드

## 사전 요구사항
- Git 2.0 이상
- Node.js 14.0 이상 (선택사항)
- MCP CLI 도구

## 설치 방법

### 1. 저장소 클론
```bash
git clone https://github.com/EJCHO-salary/testTemp.git
cd testTemp
```

### 2. 브랜치 확인
```bash
git branch -a
```

### 3. 원격 저장소 설정
```bash
git remote add origin https://github.com/EJCHO-salary/testTemp.git
```

## 실행 방법

### 기본 워크플로우
1. 새 브랜치 생성: `git checkout -b feature/new-feature`
2. 변경사항 작업
3. 커밋: `git commit -m "feat: 새 기능"`
4. 푸시: `git push origin feature/new-feature`

## 문제 해결
- 충돌 발생 시: `git status`로 충돌 파일 확인
- 병합 취소: `git merge --abort`