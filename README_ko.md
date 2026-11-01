# prompt-stash

제가 실제로 쓰는 프롬프트 중 쓸만한 것들을 공유합니다.

각 서비스의 지침 입력란에만 두면 변경 내역을 비교하거나 다른 환경에서 다시 쓰기 어렵습니다. 그래서 괜찮은 프롬프트를 Markdown 파일로 보관하고, 필요할 때 복사해 수정할 수 있게 정리했습니다.

향후 다른 프롬프트도 추가할 수 있습니다.

영문 문서는 [README.md](README.md)에 있습니다.

## 프롬프트

| 프롬프트 | 최신 버전 | 대상 | 설명 |
| --- | --- | --- | --- |
| [Codex](codex/readme.md) | [`v1.0.0`](codex/v1.0.0.md) | Codex 앱 / IDE 확장 | `model_instructions_file`로 불러오는 전체 지침입니다. |
| [Glaude](Glaude%20%28GPTs%29/readme.md) | [`v1.3.0`](Glaude%20%28GPTs%29/v1.3.0.md) | ChatGPT GPTs | Glaude GPT에 사용한 한국어 중심 프롬프트입니다. |
| [GemInteg](GemInteg/) | [`v1.0.0`](GemInteg/v1.0.0%20%28한국어%29.md) | Gemini | Gemini의 성실성·검색·오류 인정 방식을 강화하는 응답 지침입니다. |

## 사용 방법

1. 사용할 프롬프트 폴더를 엽니다.
2. 폴더별 README에서 적용 대상과 주의점을 확인합니다.
3. 최신 `v*.md` 파일을 복사합니다.
4. 이름, 경로, 도구, 말투, 작업 흐름 등을 자신의 환경에 맞게 수정합니다.

구체적인 적용 방법은 프롬프트마다 달라질 수 있어서 각 폴더 README에 따로 뒀습니다.

## 버전 관리

각 프롬프트는 별도 폴더에 두고, 폴더 안에 `readme.md`와 버전 파일을 둡니다.
프롬프트 파일 이름은 `vMAJOR.MINOR.PATCH.md` 형식을 사용합니다. 이전 버전도
남겨 두어 변경 내용을 비교할 수 있게 했습니다.

## 참고

- 이 프롬프트들은 제 작업 방식과 취향을 반영합니다. 그대로 쓰기 전에 내용을 검토해 주세요.
- 당연하게도 이 저장소는 각 제품 운영사의 공식 자료가 아닙니다.

## 연락처

gyugyum@gmail.com

## 라이선스

프롬프트 본문은
[Creative Commons Attribution 4.0 International][cc-by-4]
(CC BY 4.0)에 따라 배포합니다.

권장 표기:

> Prompt content by hehee9, licensed under CC BY 4.0.

자세한 내용은 [LICENSE.md](LICENSE.md)를 확인해 주세요.

[cc-by-4]: https://creativecommons.org/licenses/by/4.0/
