# Full-GPT

## How to Start

### 파이썬 가상환경에 세팅

> anaconda3 로 가상환경 구성

+ 의존성 라이브러리들이 python 3.10 버전에서 호환
```
conda create -n full-gpt python=3.10
conda activate full-gpt
```

+ 의존성 라이브러리들 설치
```
pip install -r requirements.txt
```


### 환경변수 
+ copy .env.sample .env 
```
OPENAI_API_KEY=[your key]
```