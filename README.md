# 00.dotnet_framework
00.dotnet_framework


Visual Studio 2022에서는 Visual Studio 2008의 "Visual C# / Windows" 프로젝트 스타일을 정확히 동일한 형태로는 만들 수 없지만, 거의 동일한 환경을 구성할 수 있습니다. 아래에 단계별로 정리해 드릴게요.

🔹 Visual Studio 2008의 "Visual C#/Windows" 프로젝트란?
Visual Studio 2008에서는 다음과 같은 형태로 프로젝트를 만들었습니다:

Windows Forms Application

Console Application

Class Library

.NET Framework 버전은 주로 2.0, 3.0, 3.5

✅ Visual Studio 2022에서 비슷한 환경으로 프로젝트 만드는 방법
1. Visual Studio 실행 → 새 프로젝트 만들기
시작 화면에서 [새 프로젝트 만들기] 클릭

2. 템플릿 검색
상단 검색창에 Windows Forms App (.NET Framework) 입력

"Windows Forms App (.NET Framework)" 선택
(중요: .NET Framework가 붙은 걸 선택해야 VS2008 스타일과 유사해집니다. .NET 6/7은 WPF 스타일입니다.)

3. 프로젝트 이름 및 위치 설정
원하는 이름과 저장 경로 입력 후 [만들기] 클릭

4. .NET Framework 버전 선택
생성 시 뜨는 화면에서 .NET Framework 3.5 또는 4.0 선택 가능 (2008과 가장 유사한 버전)

만약 .NET Framework 3.5나 4.0이 목록에 없으면 아래 방법으로 설치

🔧 .NET Framework 3.5 / 4.0 설치 방법
Visual Studio 상단 메뉴 > 도구 > 도구 및 기능 가져오기

Visual Studio 설치 관리자 열림 → 설치된 인스턴스 옆에 [수정] 클릭

개별 구성 요소 탭으로 이동

아래 항목 체크:

.NET Framework 3.5 개발 도구

.NET Framework 4 targeting pack 등
