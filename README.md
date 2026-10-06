# wp-image — 워드프레스용 이미지

워드프레스 글에서 아래 주소로 이미지를 건다.

```
https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/<경로>
```

- `thumbnails/<글id>.png` — 글 썸네일(1280×720)
- `posts/<글id>/<글id>-<그림이름>.png` — 본문 그림
- `icons/icon-<이름>.png` — 기능 아이콘(512×512, 투명). 원본 2160px은 image 저장소 `feature-icons/`
- `empty/empty-<이름>.png` — 빈 화면 그림(640×483, 투명)
- `unused/<원래 이름>` — 워드프레스에 올라가 있었지만 어느 글에도 쓰이지 않는 그림(분류 안 함)
- `wp-uploads-map.csv` — 워드프레스 첨부 경로 → 이 저장소 경로 대조표
- 초안 글은 `draft-…` 글id를 임시로 쓴다(발행되면 정식 글id로 옮긴다)
- 글id는 영문(예: `sijak-legal`). 어떤 글인지는 아래 표와 `urls.csv`의 한글 슬러그로 짝지어 둔다.

주의: jsDelivr는 `@main` 주소를 최대 약 12시간 저장해 두고 보여 준다. 그림을 고칠 때는 같은 이름으로 덮어쓰지 말고 `-v2`처럼 이름을 바꿔 올린다.

## 본문 그림 (375)

파일 이름은 번호가 아니라 그림마다 고유이름 `<글id>-<그림이름>`이다. 그림이 글 중간에 새로 들어가도 다른 그림 이름은 바뀌지 않는다. 글 안 순서는 아래 표 순서(워드프레스 글에 나오는 차례). 여러 글에 쓰인 그림은 글마다 따로 넣었다. 옛 경로와의 짝은 `wp-uploads-map.csv`.

| 글 슬러그 | 그림 | 주소 |
|---|---|---|
| 도면오류비용 | 소통 정확도(다시 그린 그림) | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/sijak-legal/sijak-legal-communication-accuracy.png |
| 도면오류비용 | 단계별 오류 비용(다시 그린 그림) | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/sijak-legal/sijak-legal-error-cost-by-stage.png |
| 6개-방향으로-공차를-통제할-수-있게-하는-6자유도 | 데이텀 피쳐 기호(채움·빈 삼각형) | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-27-six-directions/datum-27-six-directions-datum-feature-symbol.png |
| 6개-방향으로-공차를-통제할-수-있게-하는-6자유도 | 데이텀 A·B·C 참조 위치공차 FCF | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-27-six-directions/datum-27-six-directions-fcf-position-abc.png |
| 6자유도-스마트폰 | 책상 위에 놓인 스마트폰 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-28-six-dof/datum-28-six-dof-phone-on-desk.jpg |
| 6자유도-스마트폰 | 스마트폰 좌우 이동(병진 X) | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-28-six-dof/datum-28-six-dof-phone-move-left-right.jpg |
| 6자유도-스마트폰 | 스마트폰 앞뒤 이동(병진 Y) | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-28-six-dof/datum-28-six-dof-phone-move-front-back.jpg |
| 6자유도-스마트폰 | 스마트폰 위아래 이동(병진 Z) | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-28-six-dof/datum-28-six-dof-phone-move-up-down.jpg |
| 6자유도-스마트폰 | 스마트폰 시계/반시계 방향 회전 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-28-six-dof/datum-28-six-dof-phone-rotate-clockwise.jpg |
| 6자유도-스마트폰 | 스마트폰 좌우로 기울이는 회전 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-28-six-dof/datum-28-six-dof-phone-rotate-left-right.jpg |
| 6자유도-스마트폰 | 스마트폰 앞뒤로 기울이는 회전 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-28-six-dof/datum-28-six-dof-phone-rotate-front-back.jpg |
| 6자유도-스마트폰 | 책상면이 구속하는 3가지 자유도 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-28-six-dof/datum-28-six-dof-desk-constrained-dof.jpg |
| 데이텀-피쳐의-식별 | 데이텀 피쳐 기호(채움·빈 삼각형) | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-31-feature-identification/datum-31-feature-identification-datum-feature-symbol.png |
| 데이텀-피쳐의-식별 | 서피스와 사이즈 데이텀 지시 비교 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-31-feature-identification/datum-31-feature-identification-datum-placement-surface-vs-size.png |
| 데이텀-피쳐의-식별 | 플랜지 면에서 데이텀 평면 도출 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-31-feature-identification/datum-31-feature-identification-flange-datum-plane.png |
| 데이텀-피쳐의-식별 | 원통 사이즈 피쳐에서 데이텀 축 도출 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-31-feature-identification/datum-31-feature-identification-flange-datum-axis.png |
| 데이텀-피쳐의-식별 | 블록 도면의 데이텀 지시 방법들 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-31-feature-identification/datum-31-feature-identification-datum-placement-methods-block.png |
| 데이텀-피쳐의-식별 | 플랜지 도면의 데이텀 지시 방법들 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-31-feature-identification/datum-31-feature-identification-datum-placement-methods-flange.png |
| 데이텀-피쳐의-식별 | 3D 도면에서의 데이텀 지시 예 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-31-feature-identification/datum-31-feature-identification-datum-placement-isometric.png |
| 데이텀-피쳐의-식별 | 평면 데이텀과 중심평면 데이텀 비교 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-31-feature-identification/datum-31-feature-identification-datum-plane-vs-center-plane.png |
| 데이텀-피쳐의-식별 | 어느 지름이 데이텀 축인지 모호한 예 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-31-feature-identification/datum-31-feature-identification-ambiguous-datum-axis-diameter.png |
| 데이텀-정의 | ASME 7.1 데이텀 장 개요 인용 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-33-what-is-datum/datum-33-what-is-datum-asme-datum-section-general.png |
| 데이텀-정의 | ASME 데이텀 정의 인용 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-33-what-is-datum/datum-33-what-is-datum-asme-def-datum.png |
| 데이텀-정의 | ASME 데이텀 정의 재인용 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-33-what-is-datum/datum-33-what-is-datum-asme-def-datum-revisit.png |
| 데이텀-정의 | ASME TGC(진적 대응체) 정의 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-33-what-is-datum/datum-33-what-is-datum-asme-def-true-geometric-counterpart.png |
| 데이텀-정의 | ASME 데이텀 피쳐 정의 인용 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-33-what-is-datum/datum-33-what-is-datum-asme-def-datum-feature.png |
| 데이텀-정의 | 데이텀 피쳐→TGC→데이텀 흐름 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-33-what-is-datum/datum-33-what-is-datum-datum-feature-tgc-datum-flow.png |
| 데이텀-정의 | 도면의 데이텀 피쳐 기호 표시 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-33-what-is-datum/datum-33-what-is-datum-datum-feature-symbols-drawing.png |
| 데이텀-정의 | 도면의 데이텀 참조 순서 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-33-what-is-datum/datum-33-what-is-datum-datum-reference-order-drawing.png |
| 데이텀-정의 | FCF 안의 데이텀 참조 강조 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-33-what-is-datum/datum-33-what-is-datum-datum-references-in-fcf.png |
| 데이텀-정의 | 기하공차 요약표 데이텀 열 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-33-what-is-datum/datum-33-what-is-datum-gdt-summary-table-datum.png |
| 우리가-측정에서-다루는-데이텀은-진짜-데이텀이-아 | ASME 데이텀 정의 인용 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-34-simulated-datum/datum-34-simulated-datum-asme-def-datum.png |
| 우리가-측정에서-다루는-데이텀은-진짜-데이텀이-아 | ASME 데이텀 정의 인용(배경 없음) | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-34-simulated-datum/datum-34-simulated-datum-asme-def-datum-plain.png |
| 우리가-측정에서-다루는-데이텀은-진짜-데이텀이-아 | ASME 구현 데이텀 정의 인용 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-34-simulated-datum/datum-34-simulated-datum-asme-def-simulated-datum.png |
| 우리가-측정에서-다루는-데이텀은-진짜-데이텀이-아 | 데이텀 A 기준 면윤곽 도면 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-34-simulated-datum/datum-34-simulated-datum-profile-datum-a-drawing.png |
| 우리가-측정에서-다루는-데이텀은-진짜-데이텀이-아 | 상상한 파트와 실제 제작 파트 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-34-simulated-datum/datum-34-simulated-datum-ideal-vs-actual-part.png |
| 우리가-측정에서-다루는-데이텀은-진짜-데이텀이-아 | 실제 데이텀 피쳐와 실질 데이텀 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-34-simulated-datum/datum-34-simulated-datum-actual-datum-feature.png |
| 우리가-측정에서-다루는-데이텀은-진짜-데이텀이-아 | 실질 데이텀 기준 측정 가능 여부 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-34-simulated-datum/datum-34-simulated-datum-height-gauge-actual-datum.png |
| 우리가-측정에서-다루는-데이텀은-진짜-데이텀이-아 | 정반 위에서 흔들리는 파트 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-34-simulated-datum/datum-34-simulated-datum-part-rocking-on-plate.png |
| 우리가-측정에서-다루는-데이텀은-진짜-데이텀이-아 | 시뮬레이터에서 도출된 구현 데이텀 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-34-simulated-datum/datum-34-simulated-datum-simulator-derived-datum.png |
| 우리가-측정에서-다루는-데이텀은-진짜-데이텀이-아 | 실질 vs 구현 데이텀 측정 비교 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-34-simulated-datum/datum-34-simulated-datum-actual-vs-simulated-measure.png |
| 우리가-측정에서-다루는-데이텀은-진짜-데이텀이-아 | 구현 데이텀 기준 공차영역 평가 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-34-simulated-datum/datum-34-simulated-datum-profile-zone-from-simulator.png |
| 우리가-측정에서-다루는-데이텀은-진짜-데이텀이-아 | 실질·구현 데이텀 불일치 확대 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-34-simulated-datum/datum-34-simulated-datum-datum-mismatch-closeup.png |
| 해석법-4단계 | FCF와 4단계 해석 요소 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-4step-interpretation/draft-4step-interpretation-fcf-four-elements.png |
| 해석법-4단계 | 통제대상·목표·정도·기준 4단계 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-4step-interpretation/draft-4step-interpretation-four-step-overview.png |
| 해석법-4단계 | 기하공차 종합 정리표 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-4step-interpretation/draft-4step-interpretation-gdt-summary-table.png |
| 해석법-4단계 | 정리표: 피쳐유형 강조 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-4step-interpretation/draft-4step-interpretation-summary-table-feature-type.png |
| 해석법-4단계 | 서피스/사이즈 피쳐 벤다이어그램 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-4step-interpretation/draft-4step-interpretation-surface-size-venn.png |
| 해석법-4단계 | 정리표: 공차종류 강조 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-4step-interpretation/draft-4step-interpretation-summary-table-tolerance-type.png |
| 해석법-4단계 | 공차 심볼별 통제 의미 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-4step-interpretation/draft-4step-interpretation-tolerance-symbol-meanings.png |
| 해석법-4단계 | 정리표: 공차영역 강조 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-4step-interpretation/draft-4step-interpretation-summary-table-tolerance-zone.png |
| 해석법-4단계 | 정리표: 데이텀 강조 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-4step-interpretation/draft-4step-interpretation-summary-table-datum.png |
| 기하공차-정의하기-1 | 구멍 있는 판 기본 도면 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-define-gdt-1/draft-define-gdt-1-plate-hole-drawing.png |
| 기하공차-정의하기-1 | 데이텀 피쳐 A·B·C 지정 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-define-gdt-1/draft-define-gdt-1-datum-features-abc.png |
| 기하공차-정의하기-1 | 데이텀 평면도·직각도 정의 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-define-gdt-1/draft-define-gdt-1-datum-form-orientation.png |
| 기하공차-정의하기-1 | 판 외형 사이즈 공차 지정 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-define-gdt-1/draft-define-gdt-1-basic-size-tolerance.png |
| 기하공차-정의하기-1 | 구멍 위치공차와 기본치수 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-define-gdt-1/draft-define-gdt-1-hole-position-fcf.png |
| 사이즈-노미널 | ASME 노미널 사이즈 정의 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-size-mmc-lmc/draft-size-mmc-lmc-asme-def-nominal-size.png |
| 사이즈-노미널 | 양측 균등공차 예시 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-size-mmc-lmc/draft-size-mmc-lmc-equal-bilateral-tolerance.jpg |
| 사이즈-노미널 | 한계공차 예시 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-size-mmc-lmc/draft-size-mmc-lmc-limit-dimension.jpg |
| 사이즈-노미널 | 편측공차 예시 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-size-mmc-lmc/draft-size-mmc-lmc-unilateral-tolerance.jpg |
| 사이즈-노미널 | 양측 불균등공차 예시 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-size-mmc-lmc/draft-size-mmc-lmc-unequal-bilateral-tolerance.jpg |
| 사이즈-노미널 | 일반공차 예시 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-size-mmc-lmc/draft-size-mmc-lmc-general-tolerance.jpg |
| 사이즈-노미널 | 공차 표기별 노미널 비교 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-size-mmc-lmc/draft-size-mmc-lmc-nominal-comparison.jpg |
| 사이즈-노미널 | 공차 표기별 MMC·LMC 비교 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-size-mmc-lmc/draft-size-mmc-lmc-mmc-lmc-comparison.jpg |
| (초안:MMC(LMC)에서 정의된 기하공차는 서피스 관점에서 평가한다.) | MMC 위치공차 홀 도면 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-surface-eval/draft-surface-eval-hole-position-mmc-drawing.png |
| (초안:MMC(LMC)에서 정의된 기하공차는 서피스 관점에서 평가한다.) | 불규칙하게 가공된 실제 홀 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-surface-eval/draft-surface-eval-irregular-actual-hole.png |
| (초안:MMC(LMC)에서 정의된 기하공차는 서피스 관점에서 평가한다.) | 트루포지션의 축 공차영역 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-surface-eval/draft-surface-eval-axis-tolerance-zone.png |
| (초안:MMC(LMC)에서 정의된 기하공차는 서피스 관점에서 평가한다.) | 홀의 AME와 중심축 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-surface-eval/draft-surface-eval-hole-ame-axis.png |
| (초안:MMC(LMC)에서 정의된 기하공차는 서피스 관점에서 평가한다.) | MMC 모디파이어 강조 도면 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-surface-eval/draft-surface-eval-mmc-modifier-highlight.png |
| (초안:MMC(LMC)에서 정의된 기하공차는 서피스 관점에서 평가한다.) | 트루포지션의 VC 경계 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-surface-eval/draft-surface-eval-vc-boundary.png |
| (초안:MMC(LMC)에서 정의된 기하공차는 서피스 관점에서 평가한다.) | 홀 서피스와 VC 경계 비교 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-surface-eval/draft-surface-eval-hole-surface-vs-vc.png |
| 기하공차-공차영역 | FCF의 공차영역 칸과 피쳐 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-tolerance-zone/draft-tolerance-zone-fcf-tolerance-zone-value.png |
| 기하공차-공차영역 | 평면·곡면·원통·원뿔·구 서피스 영역 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-tolerance-zone/draft-tolerance-zone-surface-types-zones.png |
| 기하공차-공차영역 | 너비형·원통형·구형 공차영역 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-tolerance-zone/draft-tolerance-zone-width-cylinder-sphere-zones.png |
| 기하공차-공차영역 | 3차원 공간 형태의 공차영역 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-tolerance-zone/draft-tolerance-zone-3d-tolerance-zones.png |
| 기하공차-공차영역 | 2차원 단면 형태의 공차영역 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-tolerance-zone/draft-tolerance-zone-2d-section-tolerance-zones.png |
| 기하공차-공차영역 | 평면공차와 진직공차 영역 비교 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-tolerance-zone/draft-tolerance-zone-flatness-vs-straightness-zone.png |
| 기하공차-공차영역 | 플랜지 도면의 공차영역 크기 표시 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-tolerance-zone/draft-tolerance-zone-flange-drawing-zone-sizes.png |
| rule-1 | ASME Rule #1 엔벨로프 원칙 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g00/gibon-g00-asme-def-rule-1.png |
| rule-1 | 구멍·핀의 엔벨로프 경계 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g00/gibon-g00-envelope-hole-pin.png |
| asme-rule2 | ASME Rule #2 RFS·RMB 기본 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g01/gibon-g01-asme-def-rule-2.png |
| asme-rule2 | 모디파이어 없는 RFS 공차 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g01/gibon-g01-fcf-rfs.png |
| asme-rule2 | 공차값 MMC 모디파이어 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g01/gibon-g01-fcf-mmc-modifier.png |
| asme-rule2 | 공차값 LMC 모디파이어 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g01/gibon-g01-fcf-lmc-modifier.png |
| asme-rule2 | 데이텀 참조 RMB 기본조건 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g01/gibon-g01-fcf-rmb-datum.png |
| asme-rule2 | 데이텀 MMB 모디파이어 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g01/gibon-g01-fcf-mmb-datum.png |
| asme-rule2 | 데이텀 LMB 모디파이어 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g01/gibon-g01-fcf-lmb-datum.png |
| fcf-배치로-결정되는-규제-대상-서피스-피쳐-vs-사이즈 | C형 블록 FCF 배치 예시 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g02/gibon-g02-c-block-fcf-placement.png |
| fcf-배치로-결정되는-규제-대상-서피스-피쳐-vs-사이즈 | 플랜지 FCF 배치 예시 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g02/gibon-g02-flange-fcf-placement.png |
| fcf-배치로-결정되는-규제-대상-서피스-피쳐-vs-사이즈 | C형 블록 서피스/사이즈 비교 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g02/gibon-g02-c-block-surface-vs-size.png |
| fcf-배치로-결정되는-규제-대상-서피스-피쳐-vs-사이즈 | 원통 서피스/사이즈 비교 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g02/gibon-g02-cylinder-surface-vs-size.png |
| fcf-배치로-결정되는-규제-대상-서피스-피쳐-vs-사이즈 | 서피스/사이즈 공차 벤다이어그램 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g02/gibon-g02-surface-size-venn.png |
| fcf-배치로-결정되는-규제-대상-서피스-피쳐-vs-사이즈 | 표면요소와 중심요소 통제 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g02/gibon-g02-surface-vs-center-element.png |
| fcf-읽는-방법 | FCF 구조: 대상·목표·정도·기준 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g03/gibon-g03-fcf-structure.png |
| fcf-읽는-방법 | 단어·문장·문단·글 비유 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g03/gibon-g03-gdt-language-analogy.png |
| fcf-읽는-방법 | 플랜지 도면의 FCF 모음 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g03/gibon-g03-flange-drawing-fcfs.png |
| fcf-읽는-방법 | 바닥면 평면공차 FCF 읽기 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g03/gibon-g03-fcf-flatness-bottom.png |
| fcf-읽는-방법 | 보스 상면 면윤곽 FCF 읽기 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g03/gibon-g03-fcf-profile-boss-top.png |
| fcf-읽는-방법 | 보스 외경 수직공차 FCF 읽기 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g03/gibon-g03-fcf-perpendicularity-boss.png |
| fcf-읽는-방법 | 내경 위치공차 FCF 읽기 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g03/gibon-g03-fcf-position-bore.png |
| fcf-읽는-방법 | 6개 패턴홀 위치공차 FCF 읽기 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g03/gibon-g03-fcf-position-pattern-holes.png |
| fcf-읽는-방법 | 일반 면윤곽공차 FCF 읽기 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g03/gibon-g03-fcf-general-profile.png |
| fcf-읽는-방법 | 일반 공차 적용 서피스 2곳 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g03/gibon-g03-general-profile-surfaces.png |
| fcf-피쳐-컨트롤-프레임 | 플랜지 도면 FCF 확대 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g04/gibon-g04-flange-drawing-fcf-zoom.png |
| fcf-피쳐-컨트롤-프레임 | 지시선으로 피쳐를 가리키는 FCF | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g04/gibon-g04-fcf-leader-to-feature.png |
| fcf-피쳐-컨트롤-프레임 | FCF 공차종류 칸 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g04/gibon-g04-fcf-tolerance-type-cell.png |
| fcf-피쳐-컨트롤-프레임 | 기하공차 기호 14종 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g04/gibon-g04-geometric-symbols-14.png |
| fcf-피쳐-컨트롤-프레임 | FCF 공차영역 칸 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g04/gibon-g04-fcf-tolerance-zone-cell.png |
| fcf-피쳐-컨트롤-프레임 | 너비형·원통형·구형 공차영역 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g04/gibon-g04-tolerance-zone-shapes.png |
| fcf-피쳐-컨트롤-프레임 | FCF 데이텀 피쳐 칸 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g04/gibon-g04-fcf-datum-feature-cells.png |
| fcf-피쳐-컨트롤-프레임 | 데이텀 참조 개수별 FCF | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g04/gibon-g04-fcf-datum-reference-count.png |
| fcf-피쳐-컨트롤-프레임 | FCF 구성 요소 정리 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g04/gibon-g04-fcf-structure.png |
| 체계로서의-gdt | 치수공차 체계와 GD&T 비교표 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g05/gibon-g05-dt-vs-gdt-table.png |
| 체계로서의-gdt | 음식 일러스트와 레몬 그림 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g05/gibon-g05-food-illustrations.png |
| 체계로서의-gdt | 레몬 그리기 4단계 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g05/gibon-g05-lemon-drawing-stages.png |
| rule-1-실제-적용과-검사방법 | 재료상태별 허용 모양편차 그래프 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g06/gibon-g06-rule-1-form-deviation-graph.png |
| rule-1-실제-적용과-검사방법 | 핀게이지로 홀 Rule #1 검사 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g06/gibon-g06-pin-gauge-hole-check.png |
| rule-1-실제-적용과-검사방법 | 링게이지로 핀 Rule #1 검사 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g06/gibon-g06-ring-gauge-pin-check.png |
| 공차편차오차-기하공차-필수-용어-정리 | 공차 용어 정의 카드 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g08/gibon-g08-term-card-tolerance.png |
| 공차편차오차-기하공차-필수-용어-정리 | 편차 용어 정의 카드 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g08/gibon-g08-term-card-deviation.png |
| 공차편차오차-기하공차-필수-용어-정리 | 오차 용어 정의 카드 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g08/gibon-g08-term-card-error.png |
| 공차편차오차-기하공차-필수-용어-정리 | 설계·제조·검사 단계 흐름 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g08/gibon-g08-design-make-inspect-flow.png |
| 공차편차오차-기하공차-필수-용어-정리 | 도면·성적서·분석보고서 비교 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g08/gibon-g08-drawing-report-analysis.png |
| 원페이지-기하공차-1-page-gdt | 1페이지 GD&T 요약표 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g09/gibon-g09-gdt-summary-table.png |
| 기하공차-gdt-시작-fcf | 퍼즐·책·음악 비유 그림 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g10/gibon-g10-puzzle-book-music-analogy.png |
| 기하공차-gdt-시작-fcf | 플랜지 기하공차 도면 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g10/gibon-g10-flange-drawing.png |
| 기하공차-gdt-시작-fcf | 플랜지 도면 FCF 확대 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g10/gibon-g10-flange-drawing-fcf-zoom.png |
| 기하공차-gdt-시작-fcf | 플랜지 도면 데이텀 확대 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g10/gibon-g10-flange-drawing-datum-zoom.png |
| 베이직-치수-일반-치수-비교 | 베이직 치수와 일반 치수 도면 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g11/gibon-g11-basic-vs-toleranced-dim.png |
| 베이직-치수-일반-치수-비교 | 데이텀 유무에 따른 윤곽공차 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g11/gibon-g11-profile-with-without-datum.png |
| 베이직-치수-일반-치수-비교 | 베이직 치수 추가 전후 비교 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g11/gibon-g11-profile-add-basic-dim.png |
| 베이직-치수-일반-치수-비교 | 베이직 치수 vs ± 치수 비교 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g11/gibon-g11-basic-vs-plus-minus.png |
| 베이직-치수-일반-치수-비교 | 사이즈공차와 윤곽공차 분리 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g11/gibon-g11-size-and-profile-split.png |
| 베이직-치수 | 베이직 치수와 일반 치수 표기 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g12/gibon-g12-basic-dim-symbol.png |
| 베이직-치수 | 베이직 치수 표기 방법 3가지 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g12/gibon-g12-basic-dim-methods.png |
| 베이직-치수 | 직교좌표계와 극좌표계 치수 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g12/gibon-g12-cartesian-vs-polar.png |
| 베이직-치수 | 기준치수법과 체인치수법 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g12/gibon-g12-baseline-vs-chain.png |
| 베이직-치수의-완전한-이해-개념부터-트루-포지션 | ASME 베이직 치수 정의 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g13/gibon-g13-asme-def-basic-dimension.png |
| 베이직-치수의-완전한-이해-개념부터-트루-포지션 | ASME 공차 있는 치수 정의 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g13/gibon-g13-asme-def-directly-toleranced.png |
| 베이직-치수의-완전한-이해-개념부터-트루-포지션 | 일반공차 자릿수별 표 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g13/gibon-g13-general-tolerance-table.png |
| 베이직-치수의-완전한-이해-개념부터-트루-포지션 | ASME 암시 베이직 치수 규칙 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g13/gibon-g13-asme-implied-basic-rules.png |
| 베이직-치수의-완전한-이해-개념부터-트루-포지션 | ASME 트루 프로파일 정의 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g13/gibon-g13-asme-def-true-profile.png |
| 베이직-치수의-완전한-이해-개념부터-트루-포지션 | 암시적 베이직 치수 도면 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g13/gibon-g13-implied-basic-dimensions.png |
| 베이직-치수의-완전한-이해-개념부터-트루-포지션 | ASME 트루 포지션 정의 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g13/gibon-g13-asme-def-true-position.png |
| 베이직-치수의-완전한-이해-개념부터-트루-포지션 | 좌표로 표기한 베이직 치수 도면 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g13/gibon-g13-explicit-basic-dimensions.png |
| 사이즈-피쳐 | 내측 피쳐와 캘리퍼 측정 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g14/gibon-g14-internal-features-caliper.png |
| 사이즈-피쳐 | 외측 피쳐와 캘리퍼 측정 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g14/gibon-g14-external-features-caliper.png |
| 사이즈-피쳐 | 슬롯과 레일 형상 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g14/gibon-g14-slot-rail-blocks.png |
| 사이즈-피쳐 | 내측 사이즈 피쳐 강조 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g14/gibon-g14-internal-size-features.png |
| 사이즈-피쳐 | 외측 사이즈 피쳐 강조 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g14/gibon-g14-external-size-features.png |
| 사이즈-피쳐 | 사이즈 피쳐 유형과 중심요소 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g14/gibon-g14-size-feature-types-center.png |
| 사이즈-피쳐의-성립조건 | 캘리퍼로 보는 사이즈 피쳐 판별 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g15/gibon-g15-size-feature-caliper-check.png |
| 사이즈-피쳐의-성립조건 | 외측 사이즈 피쳐(축·각형)와 측정 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g15/gibon-g15-external-size-features.png |
| 사이즈-피쳐의-성립조건 | 내측 사이즈 피쳐(홀·각홀)와 측정 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g15/gibon-g15-internal-size-features.png |
| 사이즈-피쳐의-성립조건 | 반원 홀의 사이즈 피쳐 성립 여부 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g15/gibon-g15-partial-hole-size-feature.png |
| 서피스-피쳐-사이즈-피쳐-비교 | 플랜지 실물과 도면 의미 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g16/gibon-g16-flange-part-vs-drawing.png |
| 서피스-피쳐-사이즈-피쳐-비교 | 플랜지 평면·원통 서피스 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g16/gibon-g16-flange-surface-types.png |
| 서피스-피쳐-사이즈-피쳐-비교 | 서피스 피쳐와 표면요소 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g16/gibon-g16-surface-feature-element.png |
| 서피스-피쳐-사이즈-피쳐-비교 | 사이즈 피쳐와 중심요소 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g16/gibon-g16-size-feature-element.png |
| 서피스-피쳐-사이즈-피쳐-비교 | 너비형·원통형·구형 피쳐 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g16/gibon-g16-size-feature-types.png |
| 서피스-피쳐-사이즈-피쳐-비교 | 서피스/사이즈 공차 벤다이어그램 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g16/gibon-g16-surface-size-venn.png |
| 서피스-해석-vs-중심축-해석-측정방법이-다르면-해석 | 서피스 해석과 중심축 해석 비교 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g17/gibon-g17-surface-vs-axis-interpretation.png |
| 서피스-해석-vs-중심축-해석-측정방법이-다르면-해석 | 서피스 해석의 VC 경계 크기 계산 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g17/gibon-g17-virtual-condition-calc.png |
| 서피스-해석-vs-중심축-해석-측정방법이-다르면-해석 | 중심축 해석의 보너스 공차 공식 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g17/gibon-g17-bonus-tolerance-formula.png |
| 서피스-해석-vs-중심축-해석-측정방법이-다르면-해석 | 실제 사이즈별 허용 공차 그래프 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g17/gibon-g17-bonus-tolerance-graph.png |
| 서피스-해석-vs-중심축-해석-측정방법이-다르면-해석 | 실제 사이즈 20.2/20.35 공차 계산 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g17/gibon-g17-bonus-tolerance-examples.png |
| 서피스-피쳐-비교 | 플랜지 부품 형상 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g18/gibon-g18-flange-part.png |
| 서피스-피쳐-비교 | 플랜지를 구성하는 피쳐들 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g18/gibon-g18-flange-features.png |
| 서피스-피쳐-비교 | 플랜지 기하공차 도면 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g18/gibon-g18-flange-drawing.png |
| 서피스-피쳐-비교 | 피쳐별 적용 FCF | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g18/gibon-g18-flange-features-fcf.png |
| 서피스-피쳐-비교 | 플랜지 데이텀 피쳐 A·B | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g18/gibon-g18-flange-datum-features.png |
| 도면에-없으면-없는-것이다 | 단차 블록 ± 치수 표기 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g19/gibon-g19-step-block-plus-minus.png |
| 도면에-없으면-없는-것이다 | 치수 측정 기준점 표시 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g19/gibon-g19-step-block-origin.png |
| 도면에-없으면-없는-것이다 | 데이텀과 면윤곽 적용 도면 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g19/gibon-g19-step-block-profile-datum.png |
| 피쳐-정의 | FCF가 가리키는 대상 피쳐 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g20/gibon-g20-fcf-target-feature.png |
| 피쳐-정의 | ASME 피쳐 정의 인용 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g20/gibon-g20-asme-def-feature.png |
| 피쳐-정의 | 구·원통·육면체 형상 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g20/gibon-g20-sphere-cylinder-cube.png |
| 피쳐-정의 | 육면체와 평판 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g20/gibon-g20-cube-and-plate.png |
| 피쳐-정의 | 원통·평판의 홀과 핀 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g20/gibon-g20-hole-pin-pairs.png |
| 피쳐-정의 | 평판의 서피스 개수 세기 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g20/gibon-g20-plate-surface-count.png |
| 피쳐-정의 | 슬롯과 레일 피쳐 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g20/gibon-g20-slot-and-rail.png |
| 기하공차-해석-1 | 해석할 플랜지 도면 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-1/haeseok-1-flange-drawing.png |
| 기하공차-해석-1 | 앞면을 데이텀 피쳐 A로 선정 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-1/haeseok-1-datum-a-front-face.png |
| 기하공차-해석-1 | 데이텀 A를 참조하는 FCF | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-1/haeseok-1-datum-a-references.png |
| 기하공차-해석-1 | 데이텀 A 평면공차 0.1 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-1/haeseok-1-datum-a-flatness.png |
| 기하공차-해석-1 | 실린더 외면을 데이텀 B로 선정 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-1/haeseok-1-datum-b-cylinder.png |
| 기하공차-해석-1 | 데이텀 피쳐 B에 의한 데이텀 축 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-1/haeseok-1-datum-b-axis.png |
| 기하공차-해석-1 | 데이텀 B를 참조하는 FCF | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-1/haeseok-1-datum-b-references.png |
| 기하공차-해석-1 | 보스 사이즈·수직공차 규제 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-1/haeseok-1-boss-size-perpendicularity.png |
| 기하공차-해석-1 | 중앙 홀 사이즈·위치공차 규제 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-1/haeseok-1-bore-size-position.png |
| 기하공차-해석-1 | 4개 홀 사이즈·위치공차 규제 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-1/haeseok-1-holes-size-position.png |
| 기하공차-해석-1 | 공차영역 0 MMC 위치공차 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-1/haeseok-1-zero-tolerance-mmc.png |
| 기하공차-해석-1 | 데이텀 피쳐 B의 MMB 참조 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-1/haeseok-1-datum-b-mmb.png |
| 기하공차-해석-1 | 보스 수직공차 규제 다시 보기 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-1/haeseok-1-boss-perpendicularity-recap.png |
| 기하공차-해석-1 | 외경에 적용된 일반 윤곽공차 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-1/haeseok-1-general-profile-od.png |
| 기하공차-해석-1 | 뒷면 면윤곽공차 0.5 규제 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-1/haeseok-1-profile-back-face.png |
| 기하공차-해석-3-원통형-피쳐 | 해석할 홀 위치공차 FCF | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-3/haeseok-3-hole-position-fcf.png |
| 기하공차-해석-3-원통형-피쳐 | 1단계: 피쳐 유형은 사이즈 피쳐 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-3/haeseok-3-feature-type-size.png |
| 기하공차-해석-3-원통형-피쳐 | 2단계: 공차 종류는 위치공차 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-3/haeseok-3-tolerance-type-position.png |
| 기하공차-해석-3-원통형-피쳐 | 3단계: 원통형 공차영역 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-3/haeseok-3-cylindrical-tolerance-zone.png |
| 기하공차-해석-3-원통형-피쳐 | 4단계: 1차 데이텀 A에 수직 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-3/haeseok-3-primary-datum-a.png |
| 기하공차-해석-3-원통형-피쳐 | 2차 데이텀 B에서 20 떨어진 곳 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-3/haeseok-3-secondary-datum-b.png |
| 기하공차-해석-3-원통형-피쳐 | 3차 데이텀 C에서 20 떨어진 곳 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-3/haeseok-3-tertiary-datum-c.png |
| 기하공차-해석-3-원통형-피쳐 | 데이텀 체계 속 공차영역 평가 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-3/haeseok-3-zone-in-datum-frame.png |
| 기하공차-해석-4-너비형-피쳐 | 12개 슬롯 디스크의 해석 대상 FCF | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-4/haeseok-4-slotted-disc-fcf.jpg |
| 기하공차-해석-4-너비형-피쳐 | 피쳐 유형 판별: 사이즈 피쳐 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-4/haeseok-4-feature-type-size.jpg |
| 기하공차-해석-4-너비형-피쳐 | 공차 종류 판별: 위치공차 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-4/haeseok-4-tolerance-type-position.jpg |
| 기하공차-해석-4-너비형-피쳐 | 공차영역 형상: 너비형 0.5 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-4/haeseok-4-zone-shape-width.jpg |
| 기하공차-해석-4-너비형-피쳐 | 데이텀 평면 A에 수직인 공차영역 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-4/haeseok-4-zone-orientation-datum-a.jpg |
| 기하공차-해석-4-너비형-피쳐 | 데이텀 축 B를 지나는 공차영역 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-4/haeseok-4-zone-location-datum-b.jpg |
| 기하공차-해석-4-너비형-피쳐 | 12개 중심평면 30° 간격 배치 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-4/haeseok-4-zone-12x-30deg-spacing.jpg |
| 기하공차-해석-4-너비형-피쳐 | 최종 너비 0.5 공차영역 12개 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-4/haeseok-4-final-width-zones.jpg |
| 기하공차-해석-4-너비형-피쳐 | 슬롯 중심평면의 FCF 만족 평가 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-4/haeseok-4-slot-center-plane-check.jpg |
| 기하공차-해석-5-구형-피쳐 | 볼 스터드의 해석 대상 FCF | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-5/haeseok-5-ball-stud-fcf.jpg |
| 기하공차-해석-5-구형-피쳐 | 피쳐 유형 판별: 구 사이즈 피쳐 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-5/haeseok-5-feature-type-sphere.jpg |
| 기하공차-해석-5-구형-피쳐 | 공차 종류 판별: 위치공차 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-5/haeseok-5-tolerance-type-position.jpg |
| 기하공차-해석-5-구형-피쳐 | 공차영역 형상: 구형 SØ0.5 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-5/haeseok-5-zone-shape-spherical.jpg |
| 기하공차-해석-5-구형-피쳐 | 데이텀 평면 A에서 35 떨어진 위치 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-5/haeseok-5-zone-location-datum-a.jpg |
| 기하공차-해석-5-구형-피쳐 | 데이텀 축 B에 일치하는 위치 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-5/haeseok-5-zone-location-datum-b.jpg |
| 기하공차-해석-5-구형-피쳐 | 최종 지름 0.5 구형 공차영역 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-5/haeseok-5-final-spherical-zone.jpg |
| 기하공차-해석-5-구형-피쳐 | 구 중심점의 FCF 만족 평가 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-5/haeseok-5-sphere-center-check.jpg |
| 기하공차-해석-6-mmc-패턴홀 | 해석 대상 패턴홀 FCF | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-6/haeseok-6-pattern-hole-drawing.png |
| 기하공차-해석-6-mmc-패턴홀 | 1단계: 사이즈 피쳐 판별 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-6/haeseok-6-feature-type-size.png |
| 기하공차-해석-6-mmc-패턴홀 | 1단계: 중심축 통제 확인 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-6/haeseok-6-feature-type-center-axis.png |
| 기하공차-해석-6-mmc-패턴홀 | 2단계: 위치공차 선택 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-6/haeseok-6-tolerance-type-position.png |
| 기하공차-해석-6-mmc-패턴홀 | 3단계: 원통형 공차영역 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-6/haeseok-6-tolerance-zone-cylindrical.png |
| 기하공차-해석-6-mmc-패턴홀 | 3단계: 공차영역 직경 0.5 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-6/haeseok-6-tolerance-zone-diameter.png |
| 기하공차-해석-6-mmc-패턴홀 | MMC 보너스공차 그래프 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-6/haeseok-6-mmc-bonus-graph.png |
| 기하공차-해석-6-mmc-패턴홀 | DRF 이전 자유 부품 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-6/haeseok-6-drf-free-part.png |
| 기하공차-해석-6-mmc-패턴홀 | 데이텀 A 평면 구축 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-6/haeseok-6-drf-datum-a.png |
| 기하공차-해석-6-mmc-패턴홀 | 데이텀 B 평면 구축 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-6/haeseok-6-drf-datum-b.png |
| 기하공차-해석-6-mmc-패턴홀 | 데이텀 C 평면 구축 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-6/haeseok-6-drf-datum-c.png |
| 기하공차-해석-6-mmc-패턴홀 | 완성된 DRF 공간 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-6/haeseok-6-drf-complete.png |
| 기하공차-해석-6-mmc-패턴홀 | 트루포지션: A 기준 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-6/haeseok-6-true-position-datum-a.png |
| 기하공차-해석-6-mmc-패턴홀 | 트루포지션: A에 수직 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-6/haeseok-6-true-position-perpendicular-a.png |
| 기하공차-해석-6-mmc-패턴홀 | 트루포지션: B 기준 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-6/haeseok-6-true-position-datum-b.png |
| 기하공차-해석-6-mmc-패턴홀 | 트루포지션: B로부터 22 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-6/haeseok-6-true-position-basic-22.png |
| 기하공차-해석-6-mmc-패턴홀 | 트루포지션: C 기준 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-6/haeseok-6-true-position-datum-c.png |
| 기하공차-해석-6-mmc-패턴홀 | 트루포지션 위치 확정 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-6/haeseok-6-true-position-complete.png |
| 기하공차-해석-6-mmc-패턴홀 | 트루포지션의 공차영역 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-6/haeseok-6-zone-at-true-position.png |
| 기하공차-해석-6-mmc-패턴홀 | 모디파이어로 VC경계 생성 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-6/haeseok-6-vc-boundary-created.png |
| 기하공차-해석-6-mmc-패턴홀 | VC경계 크기 계산 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-6/haeseok-6-vc-size-calculation.png |
| 기하공차-해석-6-mmc-패턴홀 | DRF 내 VC경계 위치 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-6/haeseok-6-vc-boundary-located.png |
| 기하공차-해석-6-mmc-패턴홀 | 자유도 없는 VC경계 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-6/haeseok-6-vc-boundary-fixed.png |
| 기하공차-해석-6-mmc-패턴홀 | 서피스와 VC경계 평가 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-6/haeseok-6-vc-surface-evaluation.png |
| 기하공차-해석-6-mmc-패턴홀 | 치공구 평가 준비 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-6/haeseok-6-gauge-setup.png |
| 기하공차-해석-6-mmc-패턴홀 | 치공구 데이텀 A 접촉 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-6/haeseok-6-gauge-datum-a.png |
| 기하공차-해석-6-mmc-패턴홀 | 치공구 데이텀 B 접촉 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-6/haeseok-6-gauge-datum-b.png |
| 기하공차-해석-6-mmc-패턴홀 | 치공구 데이텀 C 접촉 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-6/haeseok-6-gauge-datum-c.png |
| 기하공차-해석-6-mmc-패턴홀 | 치공구 핀 삽입 평가 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-6/haeseok-6-gauge-pins-inserted.png |
| 기하공차-해석하기-7-6개의-패턴홀 | 6개 패턴홀 플랜지 도면 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-7/haeseok-7-flange-6-holes-drawing.png |
| 기하공차-해석하기-7-6개의-패턴홀 | 위치공차 FCF 구성 요소 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-7/haeseok-7-fcf-breakdown.png |
| 기하공차-해석하기-7-6개의-패턴홀 | 6개 홀 패턴 피쳐와 중심축 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-7/haeseok-7-hole-pattern-axes.png |
| 기하공차-해석하기-7-6개의-패턴홀 | 트루 포지션을 이루는 세 가지 위치 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-7/haeseok-7-true-position-elements.png |
| 기하공차-해석하기-7-6개의-패턴홀 | 홀 사이 위치: Ø33·60° 간격 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-7/haeseok-7-hole-pattern-spacing.png |
| 기하공차-해석하기-7-6개의-패턴홀 | 1차 데이텀 A 기준 수직 위치 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-7/haeseok-7-primary-datum-a-location.png |
| 기하공차-해석하기-7-6개의-패턴홀 | 2차 데이텀 B 기준 축 일치 위치 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-7/haeseok-7-secondary-datum-b-location.png |
| 기하공차-해석하기-7-6개의-패턴홀 | 트루 포지션 통제요소 정리표 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-7/haeseok-7-true-position-summary-table.png |
| 기하공차-해석하기-7-6개의-패턴홀 | Ø0.5 원통형 공차영역 6개 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-7/haeseok-7-position-zone-cylinders.png |
| 기하공차-해석하기-7-6개의-패턴홀 | DRF 공간에서의 검증 개념 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-7/haeseok-7-verification-drf.png |
| 기하공차-해석하기-7-6개의-패턴홀 | 데이텀별 자유도 제한과 DRF | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-7/haeseok-7-drf-dof-constraint.png |
| 기하공차-해석하기-7-6개의-패턴홀 | 부품과 DRF의 허용 자유도 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-7/haeseok-7-part-in-drf-dof.png |
| 기하공차-해석하기-7-6개의-패턴홀 | 회전 자유도 활용한 최종 검증 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-7/haeseok-7-verification-rotation.png |
| mmc-검사 | 홀 2개 있는 평판 부품 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-gauge/jaeryo-gauge-two-hole-plate.png |
| mmc-검사 | MMC 위치공차 평판 도면 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-gauge/jaeryo-gauge-plate-drawing-position-mmc.png |
| mmc-검사 | 기능 게이지 형상 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-gauge/jaeryo-gauge-functional-gauge.png |
| mmc-검사 | 게이지에 끼운 부품 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-gauge/jaeryo-gauge-part-on-gauge.png |
| mmc-검사 | 3차원 측정기 검사 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-gauge/jaeryo-gauge-cmm-inspection.png |
| 공차재료조건_rfs_mmc_lmc | RFS 의미 요약 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-intent/jaeryo-intent-rfs-summary.png |
| 공차재료조건_rfs_mmc_lmc | RFS 허용공차 그래프 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-intent/jaeryo-intent-rfs-tolerance-graph.png |
| 공차재료조건_rfs_mmc_lmc | MMC 의미 요약 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-intent/jaeryo-intent-mmc-summary.png |
| 공차재료조건_rfs_mmc_lmc | MMC 보너스공차 그래프 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-intent/jaeryo-intent-mmc-bonus-tolerance.png |
| 공차재료조건_rfs_mmc_lmc | MMC 가상경계 핀·홀 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-intent/jaeryo-intent-mmc-virtual-condition.png |
| 공차재료조건_rfs_mmc_lmc | LMC 의미 요약 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-intent/jaeryo-intent-lmc-summary.png |
| 공차재료조건_rfs_mmc_lmc | LMC 보너스공차 그래프 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-intent/jaeryo-intent-lmc-bonus-tolerance.png |
| 공차재료조건_rfs_mmc_lmc | LMC 가상경계 핀·홀 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-intent/jaeryo-intent-lmc-virtual-condition.png |
| 사이즈-피쳐의-mmc와-lmc | 내측 피쳐와 캘리퍼 측정 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-machining/jaeryo-machining-internal-features-caliper.png |
| 사이즈-피쳐의-mmc와-lmc | 외측 피쳐와 캘리퍼 측정 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-machining/jaeryo-machining-external-features-caliper.png |
| 사이즈-피쳐의-mmc와-lmc | 내측 피쳐 MMC·LMC 비교 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-machining/jaeryo-machining-internal-mmc-lmc-table.png |
| 사이즈-피쳐의-mmc와-lmc | 외측 피쳐 MMC·LMC 비교 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-machining/jaeryo-machining-external-mmc-lmc-table.png |
| 사이즈-피쳐의-mmc와-lmc | 가공 중 MMC에서 LMC로 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-machining/jaeryo-machining-machining-mmc-to-lmc.png |
| 사이즈-피쳐의-mmc와-lmc | MMC·LMC 사이즈 요약표 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-machining/jaeryo-machining-mmc-lmc-size-summary.png |
| mmb-계산과-적절한-mmb-선택 | 통제 피쳐인 보스 3D 형상 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-mmb/jaeryo-mmb-controlled-feature-boss.png |
| mmb-계산과-적절한-mmb-선택 | MMB 계산 예제 도면 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-mmb/jaeryo-mmb-mmb-example-drawing.png |
| mmb-계산과-적절한-mmb-선택 | 데이텀 피쳐 A·B·C·D 위치 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-mmb/jaeryo-mmb-datum-features-abcd.png |
| mmb-계산과-적절한-mmb-선택 | 데이텀 B MMB 참조 추적 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-mmb/jaeryo-mmb-datum-b-mmb-reference.png |
| mmb-계산과-적절한-mmb-선택 | 데이텀 B MMB 크기 11.7 계산 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-mmb/jaeryo-mmb-datum-b-mmb-calc.png |
| mmb-계산과-적절한-mmb-선택 | 데이텀 C MMB 참조 추적 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-mmb/jaeryo-mmb-datum-c-mmb-reference.png |
| mmb-계산과-적절한-mmb-선택 | 데이텀 C MMB 크기 1.8 계산 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-mmb/jaeryo-mmb-datum-c-mmb-calc.png |
| mmb-계산과-적절한-mmb-선택 | 진직공차 기준 데이텀 D MMB 8.2 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-mmb/jaeryo-mmb-datum-d-mmb-straightness.png |
| mmb-계산과-적절한-mmb-선택 | 수직공차 기준 데이텀 D MMB 8.3 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-mmb/jaeryo-mmb-datum-d-mmb-perpendicularity.png |
| mmb-계산과-적절한-mmb-선택 | 위치공차 기준 데이텀 D MMB 8.5 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-mmb/jaeryo-mmb-datum-d-mmb-position.png |
| mmb-계산과-적절한-mmb-선택 | 데이텀 D 참조 방법 세 가지 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-mmb/jaeryo-mmb-datum-reference-options.png |
| mmb-계산과-적절한-mmb-선택 | D만 참조 시 MMB 8.2 선택 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-mmb/jaeryo-mmb-option-d-only-mmb.png |
| mmb-계산과-적절한-mmb-선택 | A·D 참조 시 MMB 8.3 선택 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-mmb/jaeryo-mmb-option-a-d-mmb.png |
| mmb-계산과-적절한-mmb-선택 | A·B·D 참조 시 MMB 8.5 선택 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-mmb/jaeryo-mmb-option-abd-mmb.png |
| 공차조건-모디파이어 | MMC·LMC 모디파이어 FCF | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-modifier/jaeryo-modifier-fcf-mmc-lmc.png |
| 공차조건-모디파이어 | 돌출공차역(P) 모디파이어 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-modifier/jaeryo-modifier-fcf-projected-zone.png |
| 공차조건-모디파이어 | 접평면(T) 모디파이어 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-modifier/jaeryo-modifier-fcf-tangent-plane.png |
| 공차조건-모디파이어 | 비대칭 윤곽(U) 모디파이어 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-modifier/jaeryo-modifier-fcf-unequal-profile.png |
| 공차조건-모디파이어 | 다이나믹 프로파일(△) 모디파이어 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-modifier/jaeryo-modifier-fcf-dynamic-profile.png |
| 공차조건-모디파이어 | 자유상태(F) 모디파이어 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-modifier/jaeryo-modifier-fcf-free-state.png |
| mmc-특정재료상태 | 플랜지 도면과 3D 모델 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-state/jaeryo-state-flange-drawing-3d.png |
| mmc-특정재료상태 | 내경(내피쳐)의 MMC 사이즈 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-state/jaeryo-state-mmc-size-bore.png |
| mmc-특정재료상태 | 보스(외피쳐)의 MMC 사이즈 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-state/jaeryo-state-mmc-size-boss.png |
| mmc-특정재료상태 | 6개 패턴홀의 MMC 사이즈 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-state/jaeryo-state-mmc-size-pattern-holes.png |
| mmc-특정재료상태 | 위치공차의 MMC 모디파이어 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-state/jaeryo-state-position-mmc-modifier.png |
| mmc-특정재료상태 | 사이즈별 허용 위치편차 그래프 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-state/jaeryo-state-bonus-tolerance-chart.png |
| mmc-특정재료상태 | 데이텀 B의 MMB 참조 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-state/jaeryo-state-datum-b-mmb.png |
| 기하공차-통제목표 | 기하공차 기호 14종 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-control-target/jongryu-control-target-gdt-symbols-14.png |
| 기하공차-통제목표 | 모양공차의 통제목표 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-control-target/jongryu-control-target-form-tolerance-targets.png |
| 기하공차-통제목표 | 자세공차의 통제목표 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-control-target/jongryu-control-target-orientation-tolerance-targets.png |
| 기하공차-통제목표 | 위치공차의 통제목표 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-control-target/jongryu-control-target-position-tolerance-target.png |
| 기하공차-통제목표 | 윤곽공차의 통제목표 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-control-target/jongryu-control-target-profile-tolerance-targets.png |
| 기하공차-통제목표 | 흔들림공차의 통제목표 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-control-target/jongryu-control-target-runout-tolerance-targets.png |
| 윤곽공차의-확장-2-범위지정-비트윈-올어라운드-올 | 기본 면윤곽공차 적용 범위 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-extent/jongryu-extent-profile-surface-default.png |
| 윤곽공차의-확장-2-범위지정-비트윈-올어라운드-올 | 비트윈 범위 지정 윤곽공차 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-extent/jongryu-extent-profile-between.png |
| 윤곽공차의-확장-2-범위지정-비트윈-올어라운드-올 | 올어라운드 윤곽공차 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-extent/jongryu-extent-profile-all-around.png |
| 윤곽공차의-확장-2-범위지정-비트윈-올어라운드-올 | 올오버 윤곽공차 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-extent/jongryu-extent-profile-all-over.png |
| 기하공차-유형-특징 | 모양공차 기호 4종 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-five-types/jongryu-five-types-form-symbols.png |
| 기하공차-유형-특징 | 자세공차 기호 3종 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-five-types/jongryu-five-types-orientation-symbols.png |
| 기하공차-유형-특징 | 위치공차 기호 3종 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-five-types/jongryu-five-types-location-symbols.png |
| 기하공차-유형-특징 | 윤곽공차 기호 2종 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-five-types/jongryu-five-types-profile-symbols.png |
| 기하공차-유형-특징 | 흔들림공차 기호 2종 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-five-types/jongryu-five-types-runout-symbols.png |
| 기하공차-통제속성 | 사이즈·모양·자세·위치 측정 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-four-attributes/jongryu-four-attributes-four-attributes-gauges.png |
| 기하공차-통제속성 | 피쳐별 통제 속성 구분 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-four-attributes/jongryu-four-attributes-attribute-control-by-feature.png |
| 기하공차-통제속성 | 캘리퍼로 사이즈 피쳐 판별 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-four-attributes/jongryu-four-attributes-size-feature-caliper-check.png |
| 기하공차-통제속성 | 사이즈 편차 개념 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-four-attributes/jongryu-four-attributes-size-deviation.png |
| 기하공차-통제속성 | 모양 편차 개념 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-four-attributes/jongryu-four-attributes-form-deviation.png |
| 기하공차-통제속성 | 자세 편차 개념 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-four-attributes/jongryu-four-attributes-orientation-deviation.png |
| 기하공차-통제속성 | 위치 편차 개념 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-four-attributes/jongryu-four-attributes-location-deviation.png |
| 기하공차-통제속성 | 기하공차 요약표 통제속성 열 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-four-attributes/jongryu-four-attributes-gdt-summary-table-attributes.png |
| 윤곽공차의-확장-3-불균일한-공차영역의-정의-비트윈 | 너비 0.1 균일한 윤곽 공차영역 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-nonuniform/jongryu-nonuniform-profile-uniform-zone.png |
| 윤곽공차의-확장-3-불균일한-공차영역의-정의-비트윈 | 비트윈 구간별 윤곽공차 지시 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-nonuniform/jongryu-nonuniform-between-segments-drawing.png |
| 윤곽공차의-확장-3-불균일한-공차영역의-정의-비트윈 | 구간별 균일 너비 공차영역 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-nonuniform/jongryu-nonuniform-between-segments-zone.png |
| 윤곽공차의-확장-3-불균일한-공차영역의-정의-비트윈 | 프롬투 변하는 윤곽공차 지시 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-nonuniform/jongryu-nonuniform-from-to-drawing.png |
| 윤곽공차의-확장-3-불균일한-공차영역의-정의-비트윈 | 너비가 점차 변하는 공차영역 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-nonuniform/jongryu-nonuniform-from-to-zone.png |
| 윤곽공차의-확장-3-불균일한-공차영역의-정의-비트윈 | NONUNIFORM 윤곽공차 지시 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-nonuniform/jongryu-nonuniform-nonuniform-drawing.png |
| 윤곽공차의-확장-3-불균일한-공차영역의-정의-비트윈 | CAD 모델로 정의한 불균일 영역 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-nonuniform/jongryu-nonuniform-nonuniform-cad-zone.png |
| 윤곽공차의-확장-1-불균등-공차영역을-정의하는-ⓤ-모 | 양쪽 같은 너비 윤곽 공차영역 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-unequal-u/jongryu-unequal-u-profile-equal-bilateral.png |
| 윤곽공차의-확장-1-불균등-공차영역을-정의하는-ⓤ-모 | Ⓤ 모디파이어 지시 예제 형상 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-unequal-u/jongryu-unequal-u-u-modifier-question.png |
| 윤곽공차의-확장-1-불균등-공차영역을-정의하는-ⓤ-모 | Ⓤ0: 재료 제거 방향 공차영역 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-unequal-u/jongryu-unequal-u-u0-material-removal.png |
| 윤곽공차의-확장-1-불균등-공차영역을-정의하는-ⓤ-모 | Ⓤ0.5: 재료 추가 방향 공차영역 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-unequal-u/jongryu-unequal-u-u05-material-addition.png |
| 윤곽공차의-확장-1-불균등-공차영역을-정의하는-ⓤ-모 | Ⓤ0.1: 양쪽 다른 너비 공차영역 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-unequal-u/jongryu-unequal-u-u01-unequal-bilateral.png |
| 자전거로-알아보는-기하공차 | 자전거 타이어와 림 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/sijak-ambiguity/sijak-ambiguity-bicycle-tire-rim.jpg |
| 자전거로-알아보는-기하공차 | 타이어·림 지름 공차 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/sijak-ambiguity/sijak-ambiguity-tire-rim-size.jpg |
| 자전거로-알아보는-기하공차 | 사이즈공차와 원주편차 비교 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/sijak-ambiguity/sijak-ambiguity-wheel-size-vs-runout.jpg |
| 자전거로-알아보는-기하공차 | 휠 원주흔들림 도면 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/sijak-ambiguity/sijak-ambiguity-wheel-runout-drawing.jpg |
| 자전거로-알아보는-기하공차 | 휠 흔들림 측정 장비 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/sijak-ambiguity/sijak-ambiguity-wheel-runout-gauge.jpg |
| 치수공차의-한계 | 모호한 측정 기준면 문제 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/sijak-assembly/sijak-assembly-ambiguous-reference-edge.png |
| 치수공차의-한계 | 홀 지름 측정 방법의 모호함 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/sijak-assembly/sijak-assembly-ambiguous-hole-diameter.png |
| 치수공차의-한계 | 홀 위치 측정 기준의 모호함 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/sijak-assembly/sijak-assembly-ambiguous-hole-distance.png |
| 불량품이-합격하고-양품이-불합격되는-치수공차 | 홀과 보스 조립 형상 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/sijak-defect-pass/sijak-defect-pass-hole-boss-assembly.png |
| 불량품이-합격하고-양품이-불합격되는-치수공차 | 홀·보스 부품 도면 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/sijak-defect-pass/sijak-defect-pass-hole-boss-drawings.png |
| 불량품이-합격하고-양품이-불합격되는-치수공차 | 조립 여유 0.7 계산 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/sijak-defect-pass/sijak-defect-pass-clearance-calculation.png |
| 불량품이-합격하고-양품이-불합격되는-치수공차 | 보스 상하좌우 0.7 이동 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/sijak-defect-pass/sijak-defect-pass-boss-shift-orthogonal.png |
| 불량품이-합격하고-양품이-불합격되는-치수공차 | 보스 대각선 0.7 이동 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/sijak-defect-pass/sijak-defect-pass-boss-shift-diagonal.png |
| 불량품이-합격하고-양품이-불합격되는-치수공차 | ±0.7 사각 공차영역 도면 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/sijak-defect-pass/sijak-defect-pass-square-zone-wide.png |
| 불량품이-합격하고-양품이-불합격되는-치수공차 | 대각선 이동 시 간섭 확인 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/sijak-defect-pass/sijak-defect-pass-diagonal-interference-check.png |
| 불량품이-합격하고-양품이-불합격되는-치수공차 | 간섭 없는 최대 이동 위치 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/sijak-defect-pass/sijak-defect-pass-max-shift-without-interference.png |
| 불량품이-합격하고-양품이-불합격되는-치수공차 | 피타고라스로 0.5 사각 도출 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/sijak-defect-pass/sijak-defect-pass-pythagoras-square-zone.png |
| 불량품이-합격하고-양품이-불합격되는-치수공차 | ±0.5 사각 공차영역 도면 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/sijak-defect-pass/sijak-defect-pass-square-zone-narrow.png |
| 불량품이-합격하고-양품이-불합격되는-치수공차 | 공차영역 기준 합격·불합격 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/sijak-defect-pass/sijak-defect-pass-pass-fail-by-zone.png |
| 불량품이-합격하고-양품이-불합격되는-치수공차 | 조립 가능 여부와 클리어런스 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/sijak-defect-pass/sijak-defect-pass-assembly-clearance-check.png |
| 불량품이-합격하고-양품이-불합격되는-치수공차 | 측정점 분포와 합부 판정 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/sijak-defect-pass/sijak-defect-pass-measured-points-pass-fail.png |
| 불량품이-합격하고-양품이-불합격되는-치수공차 | 양품·불량품 합부 매트릭스 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/sijak-defect-pass/sijak-defect-pass-good-defect-matrix.png |
| 불량품이-합격하고-양품이-불합격되는-치수공차 | 불량품 합격·양품 불합격 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/sijak-defect-pass/sijak-defect-pass-defect-pass-good-fail.png |
| 불량품이-합격하고-양품이-불합격되는-치수공차 | 피타고라스로 Ø1.4 원 도출 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/sijak-defect-pass/sijak-defect-pass-pythagoras-circle-zone.png |
| 불량품이-합격하고-양품이-불합격되는-치수공차 | 원형 공차영역 합부 비교 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/sijak-defect-pass/sijak-defect-pass-circular-zone-matrix.png |
| 불량품이-합격하고-양품이-불합격되는-치수공차 | 사각·원형 공차영역 면적 비교 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/sijak-defect-pass/sijak-defect-pass-square-vs-circle-area.png |
| 불량품이-합격하고-양품이-불합격되는-치수공차 | 치수공차 vs 기하공차 도면 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/sijak-defect-pass/sijak-defect-pass-dimensional-vs-gdt-drawing.png |
| 도면오류비용 | 언어의 정확도 스펙트럼 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/sijak-legal/sijak-legal-language-precision-scale.png |
| 도면오류비용 | 단계별 도면오류 비용 증가 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/sijak-legal/sijak-legal-drawing-error-cost-stages.png |
| 기하공차로-좌절한-엔지니어를-위한-힐링-자기계발 | 힐링 자기계발서 목차 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/sijak-training/sijak-training-book-table-of-contents.png |

## 썸네일 (61)

| 글 슬러그 | 주소 |
|---|---|
| 6개-방향으로-공차를-통제할-수-있게-하는-6자유도 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/thumbnails/datum-27-six-directions.png |
| 6자유도-스마트폰 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/thumbnails/datum-28-six-dof.png |
| drf-역할 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/thumbnails/datum-29-drf-not-coordinate.png |
| drf-특징 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/thumbnails/datum-30-drf-real-part.png |
| 데이텀-피쳐의-식별 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/thumbnails/datum-31-feature-identification.png |
| 데이텀-역할 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/thumbnails/datum-32-datum-role.png |
| 데이텀-정의 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/thumbnails/datum-33-what-is-datum.png |
| 우리가-측정에서-다루는-데이텀은-진짜-데이텀이-아 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/thumbnails/datum-34-simulated-datum.png |
| rule-1 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/thumbnails/gibon-g00.png |
| asme-rule2 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/thumbnails/gibon-g01.png |
| fcf-배치로-결정되는-규제-대상-서피스-피쳐-vs-사이즈 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/thumbnails/gibon-g02.png |
| fcf-읽는-방법 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/thumbnails/gibon-g03.png |
| fcf-피쳐-컨트롤-프레임 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/thumbnails/gibon-g04.png |
| 체계로서의-gdt | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/thumbnails/gibon-g05.png |
| rule-1-실제-적용과-검사방법 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/thumbnails/gibon-g06.png |
| 기하공차의-문제가-아니라-측정수의-문제 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/thumbnails/gibon-g07.png |
| 공차편차오차-기하공차-필수-용어-정리 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/thumbnails/gibon-g08.png |
| 원페이지-기하공차-1-page-gdt | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/thumbnails/gibon-g09.png |
| 기하공차-gdt-시작-fcf | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/thumbnails/gibon-g10.png |
| 베이직-치수-일반-치수-비교 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/thumbnails/gibon-g11.png |
| 베이직-치수 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/thumbnails/gibon-g12.png |
| 베이직-치수의-완전한-이해-개념부터-트루-포지션 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/thumbnails/gibon-g13.png |
| 사이즈-피쳐 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/thumbnails/gibon-g14.png |
| 사이즈-피쳐의-성립조건 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/thumbnails/gibon-g15.png |
| 서피스-피쳐-사이즈-피쳐-비교 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/thumbnails/gibon-g16.png |
| 서피스-해석-vs-중심축-해석-측정방법이-다르면-해석 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/thumbnails/gibon-g17.png |
| 서피스-피쳐-비교 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/thumbnails/gibon-g18.png |
| 도면에-없으면-없는-것이다 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/thumbnails/gibon-g19.png |
| 피쳐-정의 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/thumbnails/gibon-g20.png |
| 기하공차-해석-1 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/thumbnails/haeseok-1.png |
| 기하공차-해석-3-원통형-피쳐 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/thumbnails/haeseok-3.png |
| 기하공차-해석-4-너비형-피쳐 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/thumbnails/haeseok-4.png |
| 기하공차-해석-5-구형-피쳐 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/thumbnails/haeseok-5.png |
| 기하공차-해석-6-mmc-패턴홀 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/thumbnails/haeseok-6.png |
| 기하공차-해석하기-7-6개의-패턴홀 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/thumbnails/haeseok-7.png |
| mmc-검사 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/thumbnails/jaeryo-gauge.png |
| 공차재료조건_rfs_mmc_lmc | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/thumbnails/jaeryo-intent.png |
| 사이즈-피쳐의-mmc와-lmc | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/thumbnails/jaeryo-machining.png |
| mmb-계산과-적절한-mmb-선택 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/thumbnails/jaeryo-mmb.png |
| 공차조건-모디파이어 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/thumbnails/jaeryo-modifier.png |
| mmc-특정재료상태 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/thumbnails/jaeryo-state.png |
| 기하공차-통제목표 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/thumbnails/jongryu-control-target.png |
| 윤곽공차의-확장-2-범위지정-비트윈-올어라운드-올 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/thumbnails/jongryu-extent.png |
| 기하공차-유형-특징 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/thumbnails/jongryu-five-types.png |
| 기하공차-통제속성 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/thumbnails/jongryu-four-attributes.png |
| 윤곽공차의-확장-3-불균일한-공차영역의-정의-비트윈 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/thumbnails/jongryu-nonuniform.png |
| 윤곽공차의-확장-1-불균등-공차영역을-정의하는-ⓤ-모 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/thumbnails/jongryu-unequal-u.png |
| 공차는-누가-결정하는가 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/thumbnails/sijak-adoption.png |
| 자전거로-알아보는-기하공차 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/thumbnails/sijak-ambiguity.png |
| 치수공차의-한계 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/thumbnails/sijak-assembly.png |
| 도면-조직-공통언어 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/thumbnails/sijak-common-language.png |
| 공차가-중요한-이유 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/thumbnails/sijak-cost.png |
| 불량품이-합격하고-양품이-불합격되는-치수공차 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/thumbnails/sijak-defect-pass.png |
| 치수공차와-기하공차의-근본적인-차이 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/thumbnails/sijak-difference.png |
| 설계-생산-품질-고객이-싸우는-진짜-이유 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/thumbnails/sijak-fight.png |
| 도면오류비용 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/thumbnails/sijak-legal.png |
| gdt에-대한-10가지-오해 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/thumbnails/sijak-myths.png |
| 기하공차로-좌절한-엔지니어를-위한-힐링-자기계발 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/thumbnails/sijak-training.png |
| 왜-이-값인가-기하공차-설계에서-판단-근거가-중요한 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/thumbnails/sijak-why-this-value.png |
| 공차가-필요한-이유 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/thumbnails/sijak-why-tolerance.png |
| 당신의-엔지니어링-경쟁력을-세계-수준으로-높이는 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/thumbnails/sijak-world-class.png |

## 기능 아이콘 (16) — 512×512 투명 PNG

| 용도 | 주소 |
|---|---|
| 분류: 시작 전에 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/icons/icon-before.png |
| 분류: 기본 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/icons/icon-fcf.png |
| 분류: 데이텀 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/icons/icon-datum.png |
| 분류: 기하공차 종류 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/icons/icon-types.png |
| 분류: 재료조건 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/icons/icon-mmc.png |
| 분류: 실전 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/icons/icon-practice.png |
| 도구: 보너스 공차 계산기 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/icons/icon-calculator.png |
| 도구: 자유도 시뮬레이터 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/icons/icon-dof.png |
| 도구: 기하공차 용어집 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/icons/icon-glossary.png |
| 도구: FCF 편집기 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/icons/icon-editor.png |
| 도구: 용어집 챗봇 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/icons/icon-chatbot.png |
| 입구: 커뮤니티 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/icons/icon-community.png |
| 입구: 질문의 전당 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/icons/icon-hall.png |
| 입구: 강의 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/icons/icon-course.png |
| 입구: 전자책 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/icons/icon-ebook.png |
| 입구: 블로그 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/icons/icon-blog.png |

## 빈 화면 그림 (3) — 640×483 투명 PNG

| 용도 | 주소 |
|---|---|
| 빈 화면: 검색 결과 없음 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/empty/empty-search.png |
| 빈 화면: 404 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/empty/empty-404.png |
| 빈 화면: 글 없음 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/empty/empty-posts.png |

## 미사용 그림 (60)

워드프레스에 올라가 있었지만 어느 글에도 쓰이지 않는 그림. 원래 이름 그대로 `unused/`에 둔다. 목록은 `urls.csv`(종류=미사용).
