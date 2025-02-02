# 코딩센세 오픈소스(CodingSense)

안녕하세요! 코딩센세입니다.
https://www.youtube.com/@coding_ez_snese

## 🎯 프로젝트 소개

코딩센세는 앱 개발을 위한 무료 교육 자료를 제공하는 오픈 소스 입니다.

## 📚 제공하는 교육 자료

### Flutter 기초
- Flutter 개발 환경 설정 가이드
- Widget 기초와 상태 관리
- UI/UX 디자인 패턴
- Flutter 네비게이션과 라우팅
- 데이터 저장과 관리
- 등...

### Riverpod 심화
- Riverpod 상태 관리 기초
- Provider 패턴 활용
- 비동기 데이터 관리
- 의존성 주입 패턴
- 테스트 작성 방법
- 등...

## ⚙️ 사용 방법

### FVM(Flutter Version Management) 설정

1. FVM 설치
```bash
# macOS & Linux
brew tap leoafarias/fvm
brew install fvm

# Windows
choco install fvm

# 또는 dart pub으로 설치
dart pub global activate fvm
```

2. Flutter 버전 설치 및 설정
```bash
# 프로젝트 디렉토리로 이동
cd your_project_directory

# 프로젝트에 지정된 Flutter 버전 설치
fvm install

# 현재 프로젝트에 Flutter 버전 적용
fvm use

# (선택사항) 전역 Flutter 버전 설정
fvm global {version}
```

3. IDE 설정 ( 문제가 발생하는 경우에만 )
   - VS Code: FVM 확장 프로그램 설치 
   - Android Studio: Flutter SDK 경로를 .fvm/flutter_sdk로 설정

### 프로젝트 실행

```bash
# 의존성 설치
fvm flutter pub get

# 개발 모드로 실행
fvm flutter run
```

## 📝 라이센스

본 저장소의 모든 교육 자료는 MIT 라이센스 하에 제공됩니다. 다음과 같은 활동이 가능합니다:

- 자유로운 사용
- 수정 및 재배포
- 상업적 활용

## 🤝 기여하기

우리는 커뮤니티의 기여를 환영합니다:

1. 새로운 교육 자료 제작
2. 기존 자료 개선 및 업데이트
3. 오류 수정
4. 번역 작업

기여하시려면 Pull Request를 보내주세요.

## 🌟 후원하기

코딩센세는 비영리로 운영되며, 모든 자료는 무료로 제공됩니다. 프로젝트 지속을 위한 후원은 다음 플랫폼을 통해 가능합니다:

[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://buymeacoffee.com/blueberry95)

여러분의 후원은 더 나은 교육 자료 제작에 사용됩니다.
