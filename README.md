# 3rd-unity-6-templete

> 과제 안내: [작업지시서 — 나만의 셰이더 제작](ASSIGNMENT.md)

## 셰이더볼 사용법

셰이더 테스트용 씬과 셰이더볼이 준비되어 있습니다.

| 경로 | 설명 |
| --- | --- |
| `Assets/00. Scenes/Study Shader.unity` | 셰이더볼 3개가 배치된 테스트 씬 |
| `Assets/01. ShaderBall/ShaderBall.prefab` | 셰이더볼 프리팹 |
| `Assets/01. ShaderBall/Materials/ShaderBall_Surface.mat` | 볼 표면에 쓰이는 기본 머티리얼 (흰색 URP Lit) |
| `Assets/01. ShaderBall/Materials/ShaderBall_Base.mat` | 받침대 · 링 · 로고용 머티리얼 (수정하지 않아도 됨) |

### 내 셰이더 적용하기

1. `Study Shader` 씬을 엽니다.
2. 셰이더를 만들고, 그 셰이더로 머티리얼을 만듭니다.
3. Hierarchy에서 `ShaderBalls > ShaderBall_1`(또는 `_2`, `_3`)을 펼칩니다.
4. 표면 파트 4개에 만든 머티리얼을 드래그해서 넣습니다.
   - `Ball/Ball_Part` (구 본체)
   - `Ball/Front_Part`, `Ball/Back_Part_1`, `Ball/Back_Part_2` (앞뒤 패널)
5. 볼 3개에 서로 다른 머티리얼을 넣으면 셰이더끼리 나란히 비교할 수 있습니다.

> 씬에 있는 볼만 바꾸면 프리팹 원본은 그대로 남습니다. 프리팹이나 `ShaderBall_Surface.mat`을 직접 수정하면 모든 볼이 함께 바뀌니 주의하세요.
