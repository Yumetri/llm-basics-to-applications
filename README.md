# LLM Basics to Applications

LLM의 기초 개념부터 실제 응용까지 단계적으로 이해하기 위한 가이드 프로젝트입니다.

이 저장소는 개인 학습, 블로그 글 작성, 예제 코드 검증, 실험 재현을 함께 고려해서 구성합니다. 각 주제는 개념 설명, 최소 예제, 실험 노트, 확장 아이디어를 함께 남기는 것을 목표로 합니다.

## Goals

- LLM의 핵심 개념을 기초부터 정리합니다.
- 토큰화, 임베딩, Transformer, 학습, 추론, 평가 흐름을 실습으로 확인합니다.
- RAG, tool calling, agent, fine-tuning 같은 응용 패턴을 작은 예제로 검증합니다.
- 블로그에 옮기기 쉬운 설명과 테스트 가능한 코드를 함께 관리합니다.

## Roadmap

1. LLM 개요와 기본 용어
2. Tokenization과 vocabulary
3. Embedding과 similarity search
4. Transformer 구조
5. Pre-training, instruction tuning, alignment
6. Prompting과 structured output
7. RAG 기본 구조
8. Function calling과 tool use
9. Agent workflow
10. Evaluation과 observability
11. Fine-tuning과 adapter 방식
12. Deployment와 비용 최적화

## Project Structure

```text
.
├── docs/       # 개념 정리, 블로그 초안, 학습 노트
├── examples/   # 주제별 실행 가능한 최소 예제
├── notebooks/  # 실험용 노트북
├── src/        # 재사용 가능한 코드
└── tests/      # 예제와 유틸리티 검증 코드
```

## Usage

아직 특정 런타임이나 프레임워크에 고정하지 않았습니다. 각 예제는 해당 폴더의 README 또는 주석에 실행 방법을 별도로 기록합니다.

권장 운영 방식:

- 개념 설명은 `docs/`에 작성합니다.
- 실행 가능한 코드는 `examples/`에 작게 분리합니다.
- 반복 실험은 `notebooks/`에서 진행합니다.
- 여러 예제에서 공유하는 코드는 `src/`로 이동합니다.
- 중요한 동작은 `tests/`에서 검증합니다.

## Repository Policy

- 공개 학습 자료로 사용할 수 있도록 설명과 코드를 함께 관리합니다.
- API key, `.env`, 로컬 데이터, 모델 산출물은 커밋하지 않습니다.
- 큰 데이터셋과 모델 파일은 별도 저장소나 외부 스토리지를 사용합니다.
- 블로그에 게시한 글은 관련 문서나 예제에 링크를 남깁니다.

## License

This project is licensed under the MIT License.
