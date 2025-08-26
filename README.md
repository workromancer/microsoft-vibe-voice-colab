# VibeVoice 1.5B on Google Colab
이 리포지토리는 Microsoft의 VibeVoice-1.5B 텍스트 음성 변환(TTS) 모델을 Google Colab에서 손쉽게 실행할 수 있는 노트북을 제공합니다. Gradio 웹 UI가 포함되어 있어, 복잡한 설정 없이 바로 모델을 사용해볼 수 있습니다.

## 주요 기능
* 간편한 실행: 클릭 몇 번으로 Colab에서 VibeVoice 모델을 배포하고 실행합니다.

* 웹 UI 제공: Gradio 기반의 직관적인 사용자 인터페이스를 통해 텍스트를 음성으로 변환합니다.

* 커스텀 음성 복제: 자신만의 음성 파일을 업로드하여 새로운 목소리를 생성하는 원샷(one-shot) 음성 복제 기능을 지원합니다.

## 필수 요구사항
VibeVoice-1.5B 모델은 약 19GB 이상의 VRAM을 필요로 합니다. 따라서 이 노트북을 원활하게 실행하려면 Google Colab Pro 또는 Pro+ 구독을 통해 NVIDIA A100 (40GB VRAM)과 같은 고사양 GPU를 할당받아야 합니다. 무료 티어의 T4 GPU에서는 메모리 부족 오류가 발생합니다.

## 사용 방법
아래 링크를 클릭하여 Google Colab 노트북을 엽니다.

[Google Colab Notebook](https://colab.research.google.com/drive/1fZvax0QYeia1jJDXJOGP69WyZw8dUl3x?usp=sharing)

Colab 메뉴에서 **[런타임] > [런타임 유형 변경]** 으로 이동하여 하드웨어 가속기가 'A100 GPU' 또는 그 이상의 고사양 GPU로 설정되었는지 확인합니다.

노트북의 모든 셀을 위에서부터 순서대로 실행합니다 (Ctrl+F9 또는 [런타임] > [모두 실행]).

마지막 셀의 실행이 완료되면, 출력 로그에 Running on public URL: https://....gradio.live 와 같은 공개 URL이 나타납니다. 이 링크를 클릭하여 웹 UI에 접속하세요.

Credits
VibeVoice Model: [Microsoft](https://github.com/microsoft/VibeVoice)


