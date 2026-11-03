# OasisW v2.0 Unity Porting

Unity Editor용 플러그인 배포 패키지입니다. 대상 엔진은 **OasisW v2.0**입니다.

## 설치

Unity Package Manager에서 **+ > Add package from git URL**을 선택하고 다음 주소를 입력합니다. Git이 설치되어 있어야 합니다.

```text
https://github.com/FITFUNS/UnityPluginForOasiswV2.git#v0.3.2
```

## 사용과 업데이트

- `Tools > OasisW v2.0 > Port Project`: 로컬 프로젝트 분석 및 준비.
- `Tools > OasisW v2.0 > Private Conversion Profile`: 별도로 제공받은 승인된 비공개 변환 프로필 선택.
- `Tools > OasisW v2.0 > Upload to OasisW v2.0`: 로그인 후 완료된 준비 결과 업로드.
- `Tools > OasisW v2.0 > Plugin Updates`: 새 릴리스 확인 및 설치.

변환 프로필이 없으면 일반 분석과 지원되는 데이터 추출만 가능합니다. 프로젝트별 변환 규칙과 바인딩은 이 배포 패키지에 포함하지 않습니다. 변환 지원 범위는 선택한 프로필에 따라 달라집니다.

공개 저장소에는 설치용 DLL, Unity 메타데이터, 패키지 정보와 이 사용 안내만 포함합니다.
