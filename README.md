# 딥러닝 프로젝트를 위한 허깅페이스 실전 가이드

- 책의 기준 경로는 `hugging-face` 디렉터리입니다.
- 데이터세트는 `datasets` 디렉터리에 있다고 가정합니다.
- 이미지 파일은 `images` 디렉터리에 있다고 가정합니다.
- 모델 파일은 `models` 디렉터리에 있다고 가정합니다.

## Notice

각각의 예제는 실행 환경 및 라이브러리/프레임워크 버전에 따라 결과가 다를 수 있습니다.

이 책에서 사용된 라이브러리/프레임워크 버전은 다음과 같습니다.

```
torch==2.2.2+cu118
torchaudio==2.2.2+cu118
torchdata==0.7.1
torchtext==0.18.0
torchvision==0.17.2+cu118
huggingface_hub==0.23.4
transformers==4.41.2
datasets==2.20.0
evaluate==0.4.2
tokenizers==0.19.1
rouge_score==0.1.2
bitsandbytes==0.43.1
trl==0.9.4
peft==0.11.1
accelerate==0.32.1
pycocotools==2.0.8
pytesseract==0.3.10
diffusers==0.29.2
sentencepiece==0.2.0
faiss==1.7.4
ray==2.31.0
optuna==3.6.1
auto_gptq==0.7.1 
optimum==1.20.0
```

일부 라이브러리/프레임워크는 안정적인(stable) 버전이 변경될 수 있으므로, 이 책에서 사용한 버전 설치가 불가능할 수 있습니다.

이런 경우 책에서 사용한 버전과 유사한 버전으로 설치합니다.

## Contacts

- 윤대희 : [s076923@gmail.com](mailto:s076923@gmail.com)
- 김동화 : [dhcycle25@gmail.com](mailto:dhcycle25@gmail.com)
- 송종민 : [whdwhd93@naver.com](mailto:whdwhd93@naver.com)
- 진현두 : [gusen0927@gmail.com](mailto:gusen0927@gmail.com)