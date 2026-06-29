# ds-mlops-assets

`ds-mlops` 디자인 시스템의 **무거운 참고 미디어·발표자료** 보관용 별도 레포.
코드 레포(`ds-mlops`)를 가볍게 유지하고 Vercel Storybook 빌드 부담을 줄이기 위해 분리한다.

## 구성

| 폴더/파일 | 내용 |
|---|---|
| `benchmarking/` | 타사 제품(DataDog·RunAI·Grafana·NVIDIA BCM·VESSL·FriendliAI) 벤치마킹 캡처·영상·스크립트 |
| `as-is-Screenshot/` | 기존 제품 as-is 화면 캡처 (MLOps·AIOps·Inference) |
| `reference/` | 제품 소개 자료 |
| `slides/` | 발표용 슬라이드 이미지 |
| `*.pptx` | 발표 자료 원본 |

## 코드 레포와의 관계

- 코드: https://github.com/smilecmk/ds-mlops
- 코드 레포의 `.gitignore`가 `docs/benchmarking/`, `docs/as-is-Screenshot/`, `docs/reference/`, `slide-*.jpg`, `*.pptx`를 제외한다.
- 이 자료들은 코드 PR과 함께 리뷰되지 않는 순수 참고자료다.
