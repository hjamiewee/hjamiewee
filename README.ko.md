# Heejeong Wee

[English](https://github.com/hjamiewee) | **한국어**

**컴퓨터 언어학자** · 코퍼스 설계 · 언어 주석 · NLP 데이터 파이프라인

주석 체계를 설계하고, 그 체계를 대량의 텍스트에 적용하는 파이프라인을 만듭니다.
낱말의 뜻, 철자-소리 대응, 형태 같은 언어학적 판단을 정확하게 세우고,
사람의 판정이 일관되고 추적 가능하며 재현되도록 관리하는 일에 집중합니다.

## 하는 일

- **주석 체계 설계** — 품사·뜻 번호, 철자-소리 대응(GPC), 음절, 형태, 어휘 관계
- **사람 판정 기반 파이프라인** — 사람의 판정을 결정 파일로 쌓고, 데이터 전체에 자동으로 일관되게 적용
- **데이터 품질 관리** — 재현 검사, 오래된 판정 감지, 번호 고정 대장
- **언어학적 분석** — 커리큘럼의 해독 가능성(decodability) 같은 지표 설계와 측정

## 대표 프로젝트

| 프로젝트 | 보여주는 것 |
|---|---|
| **[phonics-annotation-toolkit](https://github.com/hjamiewee/phonics-annotation-toolkit)** | 파닉스 지문을 소리 축(발음·GPC)과 뜻 축(품사·뜻)으로 나눠 주석하고, 레슨 타깃 판정, 음성·이미지 에셋 목록, 해독 가능성 분석까지 만듭니다. 문서는 영어·한국어 두 판입니다. |
| **[영어 재료 전치사 분류](https://github.com/hjamiewee/MA_thesis)** | 석사 논문에서 출발한 연구입니다. `made of / from / with`를 COCA 문장으로 학습한 DistilBERT로 분류해, 무학습 GPT-4o(정확도 39%, `from` 0%)보다 높은 Macro-F1 0.575를 얻었습니다. |

## 도구

Python · pandas · pytest · PyTorch · Hugging Face Transformers · scikit-learn · Google Sheets API · Git

<!-- 연락처: LinkedIn 은 나중에 연결 (## 연락처 절을 여기에 추가) -->
