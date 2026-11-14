# Quick Translate 설치 파일

글을 고르고 **Ctrl 을 누른 채 C 를 두 번** 누르면 커서 옆에 번역이 뜨는 Windows 번역기입니다.
번역은 이 컴퓨터의 그래픽카드에서 돌아가며, 글을 인터넷으로 보내지 않습니다.

## 설치

1. [Releases](../../releases/latest) 에서 `QuickTranslate-Setup.exe` 를 받아 두 번 클릭합니다 (관리자 권한 필요 없음).
   - "Windows의 PC 보호" 창이 뜨면 "추가 정보" → "실행" (서명 없는 프로그램이라 뜨는 경고).
2. 번역 모델(약 4GB)은 설치하는 동안 Hugging Face 에서 받습니다.
   인터넷이 막힌 곳이면 모델 파일 두 개를 다른 PC 에서 옮겨 와 setup.exe 와 같은 폴더에 두고 실행하세요.
3. 설치한 뒤에는 새 판이 나오면 트레이 알림으로 알려 주고, 누르면 업데이트합니다
   (트레이 메뉴에서 "업데이트 자동 설치" 를 켜면 저절로).

## 들어 있는 것과 라이선스

- 번역 모델: Gemma 4 E4B (Google, Apache 2.0) — 설치 때 [unsloth/gemma-4-E4B-it-qat-GGUF](https://huggingface.co/unsloth/gemma-4-E4B-it-qat-GGUF) 에서 받음
- 번역 엔진: [llama.cpp](https://github.com/ggml-org/llama.cpp) (MIT)
- .NET 런타임 (MIT), Visual C++ 런타임 (Microsoft 재배포 허용 파일)

이 저장소에는 설치 파일만 있습니다.
