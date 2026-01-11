![Honeycam 2026-01-11 17-19-13](https://github.com/user-attachments/assets/f5ba22bb-2c2b-493b-984c-5f38710052f1)

# DragSearch

드래그한 텍스트를 다양한 검색 엔진에서 직접 검색할 수 있는 Chrome 확장 프로그램입니다.

## 기능

- **텍스트 드래그 선택**: 웹 페이지의 텍스트를 드래그하면 검색 팝업이 자동으로 나타납니다.
- **다양한 검색 엔진 지원**:
  - Google
  - Naver
  - Baidu
  - Stack Overflow
  - GitHub
  - DuckDuckGo
  - YouTube
  - Reddit
  - Wikipedia
  - Namuwiki

## 파일 구조

```
DragSearch/
├── manifest.json      # 확장 프로그램 설정 파일
├── content.js         # 메인 기능 구현 스크립트
├── styles.css         # 팝업 스타일시트
├── README.md          # 이 파일
└── icons/
    └── icon128.png    # 확장 프로그램 아이콘
```

## 설치 방법

### Chrome에서 설치

1. Chrome 주소창에 `chrome://extensions/` 입력
2. 오른쪽 상단의 **개발자 모드** 토글 활성화
3. **압축 해제된 확장 프로그램 로드** 클릭
4. DragSearch 폴더 선택

## 사용 방법

> [!NOTE]
> - 가로 방식으로 팝업 창이 나타날 경우, "Shift" 키와 마우스 스크롤을 회전하여 검색 엔진의 아이콘을 볼 수 있습니다.
> - 세로 방식으로 팝업 창이 나타날 경우, 마우스 스크롤을 회전하여 검색 엔진의 아이콘을 볼 수 있습니다.

1. 웹 페이지에서 텍스트를 드래그하여 선택합니다.
2. 자동으로 검색 엔진 팝업이 선택 영역 근처에 나타납니다.
3. 원하는 검색 엔진의 아이콘을 클릭합니다.
4. 해당 검색 엔진에서 새 탭으로 검색 결과가 열립니다.

## 🚀 향후 계획

- [ ] 커스텀 검색 엔진 추가 기능
- [ ] 사용자 설정 옵션 (검색 엔진 선택/제외)

## Icons
- [Simple Icons](https://simpleicons.org/?q=google "Simple Icons")
