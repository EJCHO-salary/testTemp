# Git 작업 전략

## MCP를 활용한 Git 관리

### 핵심 원칙
1. **커밋 자동화**: MCP를 통한 효율적인 커밋 프로세스
2. **브랜치 관리**: 체계적인 브랜치 전략 수립
3. **충돌 해결**: 스마트한 머지 충돌 처리

### 작업 플로우

#### 기본 플로우
```bash
git add .
git commit -m "feat: 새로운 기능 추가"
git push origin main
```

#### 브랜치 작업
```bash
git checkout -b feature/new-feature
git add .
git commit -m "feat: 기능 구현"
git push -u origin feature/new-feature
```

### 모범 사례
- 명확한 커밋 메시지 작성
- 정기적인 동기화
- 코드 리뷰 프로세스 준수
- 작은 단위로 자주 커밋
