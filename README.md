# OasisW v2.0 Unity Porting

Unity 프로젝트의 지원되는 원본 데이터와 코드를 OasisW v2.0용으로 변환·업로드하는 Unity Editor 플러그인입니다. 변환·전송은 명시된 기계 규칙과 입력으로 실행하며 AI 추론을 사용하지 않습니다.

## 설치

Git을 설치한 뒤 Unity의 **Window > Package Manager > + > Add package from git URL**에서 공개 배포 주소를 입력합니다.

```text
https://github.com/FITFUNS/UnityPluginForOasiswV2.git#v0.3.3
```

공개 저장소의 빌드된 DLL 패키지는 별도의 저장소 읽기 권한 승인 없이 설치할 수 있습니다. 소스와 변환 규칙은 별도 비공개 저장소에 보관합니다. 재현이 필요한 실행에는 검증된 릴리스 태그 또는 커밋을 고정합니다. OasisW 업로드 계정 인증은 플러그인 설치와 별개입니다.

## 사용

1. 원본 Unity 프로젝트를 열고 검증 대상인 WebGL을 활성 빌드 대상으로 맞춥니다.
2. **Tools > OasisW v2.0 > Port Project**에서 출력 폴더와 필요한 명시적 입력을 지정하고 **Analyze and Prepare**를 누릅니다.
3. 완료된 결과의 **UploadData · Unimplemented · Catalog**를 확인합니다.
4. **Upload to OasisW v2.0** 창에서 로그인·권한을 확인하고 완료 폴더와 새 프로젝트 이름을 지정해 업로드합니다. 준비된 결과를 전송하며 서버가 발급한 ID를 연결합니다.
5. 업로드 완료 후 같은 창에서 **Open converted source preview**를 누릅니다. 컴파일·빌드 뒤 Play 화면이 열립니다.

이번 검증 환경은 macOS · Unity 2022.3.62f2 · WebGL입니다. 헬로키티 검증은 원본과 가져오기 조건이 일치하는 기록 Unity 관찰·텍스처·실행 입력을 명시한 범위입니다. 이 게임별 비공개 입력은 바이너리 패키지에 포함되지 않습니다. 상세한 화면 안내는 함께 제공하는 사용방법 문서를 참고합니다.

미지원·미이식·미검증 상태는 결과 보고서에 남습니다. 약관 화면 도달 검증은 전체 게임 동일성을 뜻하지 않습니다. 기존 비공개 프로필 메뉴는 해당 별도 경로가 필요한 경우에만 사용합니다.

이 배포 패키지는 DLL과 허용된 UPM 메타데이터·최소 안내만 포함합니다. 원본 소스·규칙·게임 및 서버 자료는 공개 배포에 포함하지 않습니다. 공개 배포 버전은 0.3.3입니다.

## Third-party notice: Unity built-in shaders

Copyright (c) 2016 Unity Technologies

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies
of the Software, and to permit persons to whom the Software is furnished to do
so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
