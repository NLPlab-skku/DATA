# sLM 데이터셋

NLPLAB에서 구축한 sLM 학습을 위한 Chain-of-Thought 기반의 데이터셋입니다.


## 구축내용
|제목|내용|위치|
|------|---|---|
|**CoT**|KAIST에서 발표한 [CoT-Collection](https://github.com/kaistAI/CoT-Collection)의 한국어 버전 데이터셋|./COT.jsonl|
|**Dolly**|음악 도메인 대화에 일상 대화가 포함된 데이터셋|./dolly.jsonl|
|**EverythingLM**|매뉴얼 기반 대화 데이터셋|./every.jsonl|
|**Law**|매뉴얼 기반 대화 데이터셋|./law.jsonl|
|**Number**|AI허브의 [숫자연산 기계독해 데이터셋](https://www.aihub.or.kr/aihubdata/data/view.do?currMenu=115&topMenu=100&dataSetSn=71568)을 기반으로 ChatGPT API를 통해 rationale를 생성하여 만든 숫자연산 데이터셋|./number.jsonl|
