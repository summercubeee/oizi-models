# oizi-models

오이지 앱의 폰 안 받아쓰기 모델 파일만 두는 곳입니다. 코드나 비밀은 없습니다.

| 파일 | 크기 | SHA-256 |
|---|---|---|
| model.int8.onnx | 239,233,841 | c71f0ce00bec95b07744e116345e33d8cbbe08cef896382cf907bf4b51a2cd51 |
| tokens.txt | 315,894 | f449eb28dc567533d7fa59be34e2abca8784f771850c78a47fb731a31429a1dc |

- 파일은 릴리스(태그 `sv-int8-2024-07-17`)에 있습니다. 앱은 위 SHA-256을 코드에 고정해 두고, 받은 파일이 같을 때만 씁니다.
- 원본: SenseVoice Small(FunAudioLLM)을 sherpa-onnx가 ONNX int8로 바꾼 것
  https://huggingface.co/csukuangfj/sherpa-onnx-sense-voice-zh-en-ja-ko-yue-2024-07-17 (커밋 2365baeacb507f821a0c8120fcee3d484dba7a07). 바꾸지 않고 그대로 올렸습니다.

## 라이선스
모델의 저작권과 라이선스는 원작자에게 있습니다. FunASR 모델 라이선스를 따릅니다:
https://github.com/modelscope/FunASR?tab=readme-ov-file#license
원본 저장소의 LICENSE 파일을 `LICENSE-original`로 함께 둡니다.
