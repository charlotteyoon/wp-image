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

워드프레스 첨부 그림(`sites/2/2026/…`)을 옮긴 것은 글 안에 나오는 순서대로 `-01`, `-02` … 번호를 붙였다. 여러 글에 쓰인 그림은 글마다 따로 넣었다. 옛 경로와의 짝은 `wp-uploads-map.csv`.

| 글 슬러그 | 주소 |
|---|---|
| 도면오류비용 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/sijak-legal/sijak-legal-communication-accuracy.png |
| 도면오류비용 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/sijak-legal/sijak-legal-error-cost-by-stage.png |
| 6개-방향으로-공차를-통제할-수-있게-하는-6자유도 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-27-six-directions/datum-27-six-directions-01.png |
| 6개-방향으로-공차를-통제할-수-있게-하는-6자유도 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-27-six-directions/datum-27-six-directions-02.png |
| 6자유도-스마트폰 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-28-six-dof/datum-28-six-dof-01.jpg |
| 6자유도-스마트폰 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-28-six-dof/datum-28-six-dof-02.jpg |
| 6자유도-스마트폰 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-28-six-dof/datum-28-six-dof-03.jpg |
| 6자유도-스마트폰 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-28-six-dof/datum-28-six-dof-04.jpg |
| 6자유도-스마트폰 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-28-six-dof/datum-28-six-dof-05.jpg |
| 6자유도-스마트폰 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-28-six-dof/datum-28-six-dof-06.jpg |
| 6자유도-스마트폰 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-28-six-dof/datum-28-six-dof-07.jpg |
| 6자유도-스마트폰 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-28-six-dof/datum-28-six-dof-08.jpg |
| 데이텀-피쳐의-식별 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-31-feature-identification/datum-31-feature-identification-01.png |
| 데이텀-피쳐의-식별 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-31-feature-identification/datum-31-feature-identification-02.png |
| 데이텀-피쳐의-식별 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-31-feature-identification/datum-31-feature-identification-03.png |
| 데이텀-피쳐의-식별 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-31-feature-identification/datum-31-feature-identification-04.png |
| 데이텀-피쳐의-식별 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-31-feature-identification/datum-31-feature-identification-05.png |
| 데이텀-피쳐의-식별 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-31-feature-identification/datum-31-feature-identification-06.png |
| 데이텀-피쳐의-식별 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-31-feature-identification/datum-31-feature-identification-07.png |
| 데이텀-피쳐의-식별 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-31-feature-identification/datum-31-feature-identification-08.png |
| 데이텀-피쳐의-식별 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-31-feature-identification/datum-31-feature-identification-09.png |
| 데이텀-정의 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-33-what-is-datum/datum-33-what-is-datum-01.png |
| 데이텀-정의 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-33-what-is-datum/datum-33-what-is-datum-02.png |
| 데이텀-정의 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-33-what-is-datum/datum-33-what-is-datum-03.png |
| 데이텀-정의 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-33-what-is-datum/datum-33-what-is-datum-04.png |
| 데이텀-정의 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-33-what-is-datum/datum-33-what-is-datum-05.png |
| 데이텀-정의 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-33-what-is-datum/datum-33-what-is-datum-06.png |
| 데이텀-정의 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-33-what-is-datum/datum-33-what-is-datum-07.png |
| 데이텀-정의 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-33-what-is-datum/datum-33-what-is-datum-08.png |
| 데이텀-정의 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-33-what-is-datum/datum-33-what-is-datum-09.png |
| 데이텀-정의 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-33-what-is-datum/datum-33-what-is-datum-10.png |
| 우리가-측정에서-다루는-데이텀은-진짜-데이텀이-아 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-34-simulated-datum/datum-34-simulated-datum-01.png |
| 우리가-측정에서-다루는-데이텀은-진짜-데이텀이-아 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-34-simulated-datum/datum-34-simulated-datum-02.png |
| 우리가-측정에서-다루는-데이텀은-진짜-데이텀이-아 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-34-simulated-datum/datum-34-simulated-datum-03.png |
| 우리가-측정에서-다루는-데이텀은-진짜-데이텀이-아 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-34-simulated-datum/datum-34-simulated-datum-04.png |
| 우리가-측정에서-다루는-데이텀은-진짜-데이텀이-아 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-34-simulated-datum/datum-34-simulated-datum-05.png |
| 우리가-측정에서-다루는-데이텀은-진짜-데이텀이-아 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-34-simulated-datum/datum-34-simulated-datum-06.png |
| 우리가-측정에서-다루는-데이텀은-진짜-데이텀이-아 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-34-simulated-datum/datum-34-simulated-datum-07.png |
| 우리가-측정에서-다루는-데이텀은-진짜-데이텀이-아 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-34-simulated-datum/datum-34-simulated-datum-08.png |
| 우리가-측정에서-다루는-데이텀은-진짜-데이텀이-아 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-34-simulated-datum/datum-34-simulated-datum-09.png |
| 우리가-측정에서-다루는-데이텀은-진짜-데이텀이-아 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-34-simulated-datum/datum-34-simulated-datum-10.png |
| 우리가-측정에서-다루는-데이텀은-진짜-데이텀이-아 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-34-simulated-datum/datum-34-simulated-datum-11.png |
| 우리가-측정에서-다루는-데이텀은-진짜-데이텀이-아 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/datum-34-simulated-datum/datum-34-simulated-datum-12.png |
| 해석법-4단계 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-4step-interpretation/draft-4step-interpretation-01.png |
| 해석법-4단계 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-4step-interpretation/draft-4step-interpretation-02.png |
| 해석법-4단계 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-4step-interpretation/draft-4step-interpretation-03.png |
| 해석법-4단계 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-4step-interpretation/draft-4step-interpretation-04.png |
| 해석법-4단계 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-4step-interpretation/draft-4step-interpretation-05.png |
| 해석법-4단계 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-4step-interpretation/draft-4step-interpretation-06.png |
| 해석법-4단계 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-4step-interpretation/draft-4step-interpretation-07.png |
| 해석법-4단계 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-4step-interpretation/draft-4step-interpretation-08.png |
| 해석법-4단계 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-4step-interpretation/draft-4step-interpretation-09.png |
| 기하공차-정의하기-1 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-define-gdt-1/draft-define-gdt-1-01.png |
| 기하공차-정의하기-1 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-define-gdt-1/draft-define-gdt-1-02.png |
| 기하공차-정의하기-1 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-define-gdt-1/draft-define-gdt-1-03.png |
| 기하공차-정의하기-1 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-define-gdt-1/draft-define-gdt-1-04.png |
| 기하공차-정의하기-1 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-define-gdt-1/draft-define-gdt-1-05.png |
| 사이즈-노미널 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-size-mmc-lmc/draft-size-mmc-lmc-01.png |
| 사이즈-노미널 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-size-mmc-lmc/draft-size-mmc-lmc-02.jpg |
| 사이즈-노미널 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-size-mmc-lmc/draft-size-mmc-lmc-03.jpg |
| 사이즈-노미널 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-size-mmc-lmc/draft-size-mmc-lmc-04.jpg |
| 사이즈-노미널 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-size-mmc-lmc/draft-size-mmc-lmc-05.jpg |
| 사이즈-노미널 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-size-mmc-lmc/draft-size-mmc-lmc-06.jpg |
| 사이즈-노미널 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-size-mmc-lmc/draft-size-mmc-lmc-07.jpg |
| 사이즈-노미널 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-size-mmc-lmc/draft-size-mmc-lmc-08.jpg |
| (초안:MMC(LMC)에서 정의된 기하공차는 서피스 관점에서 평가한다.) | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-surface-eval/draft-surface-eval-01.png |
| (초안:MMC(LMC)에서 정의된 기하공차는 서피스 관점에서 평가한다.) | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-surface-eval/draft-surface-eval-02.png |
| (초안:MMC(LMC)에서 정의된 기하공차는 서피스 관점에서 평가한다.) | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-surface-eval/draft-surface-eval-03.png |
| (초안:MMC(LMC)에서 정의된 기하공차는 서피스 관점에서 평가한다.) | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-surface-eval/draft-surface-eval-04.png |
| (초안:MMC(LMC)에서 정의된 기하공차는 서피스 관점에서 평가한다.) | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-surface-eval/draft-surface-eval-05.png |
| (초안:MMC(LMC)에서 정의된 기하공차는 서피스 관점에서 평가한다.) | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-surface-eval/draft-surface-eval-06.png |
| (초안:MMC(LMC)에서 정의된 기하공차는 서피스 관점에서 평가한다.) | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-surface-eval/draft-surface-eval-07.png |
| 기하공차-공차영역 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-tolerance-zone/draft-tolerance-zone-01.png |
| 기하공차-공차영역 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-tolerance-zone/draft-tolerance-zone-02.png |
| 기하공차-공차영역 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-tolerance-zone/draft-tolerance-zone-03.png |
| 기하공차-공차영역 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-tolerance-zone/draft-tolerance-zone-04.png |
| 기하공차-공차영역 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-tolerance-zone/draft-tolerance-zone-05.png |
| 기하공차-공차영역 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-tolerance-zone/draft-tolerance-zone-06.png |
| 기하공차-공차영역 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/draft-tolerance-zone/draft-tolerance-zone-07.png |
| rule-1 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g00/gibon-g00-01.png |
| rule-1 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g00/gibon-g00-02.png |
| asme-rule2 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g01/gibon-g01-01.png |
| asme-rule2 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g01/gibon-g01-02.png |
| asme-rule2 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g01/gibon-g01-03.png |
| asme-rule2 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g01/gibon-g01-04.png |
| asme-rule2 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g01/gibon-g01-05.png |
| asme-rule2 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g01/gibon-g01-06.png |
| asme-rule2 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g01/gibon-g01-07.png |
| fcf-배치로-결정되는-규제-대상-서피스-피쳐-vs-사이즈 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g02/gibon-g02-01.png |
| fcf-배치로-결정되는-규제-대상-서피스-피쳐-vs-사이즈 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g02/gibon-g02-02.png |
| fcf-배치로-결정되는-규제-대상-서피스-피쳐-vs-사이즈 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g02/gibon-g02-03.png |
| fcf-배치로-결정되는-규제-대상-서피스-피쳐-vs-사이즈 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g02/gibon-g02-04.png |
| fcf-배치로-결정되는-규제-대상-서피스-피쳐-vs-사이즈 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g02/gibon-g02-05.png |
| fcf-배치로-결정되는-규제-대상-서피스-피쳐-vs-사이즈 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g02/gibon-g02-06.png |
| fcf-읽는-방법 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g03/gibon-g03-01.png |
| fcf-읽는-방법 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g03/gibon-g03-02.png |
| fcf-읽는-방법 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g03/gibon-g03-03.png |
| fcf-읽는-방법 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g03/gibon-g03-04.png |
| fcf-읽는-방법 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g03/gibon-g03-05.png |
| fcf-읽는-방법 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g03/gibon-g03-06.png |
| fcf-읽는-방법 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g03/gibon-g03-07.png |
| fcf-읽는-방법 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g03/gibon-g03-08.png |
| fcf-읽는-방법 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g03/gibon-g03-09.png |
| fcf-읽는-방법 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g03/gibon-g03-10.png |
| fcf-피쳐-컨트롤-프레임 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g04/gibon-g04-01.png |
| fcf-피쳐-컨트롤-프레임 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g04/gibon-g04-02.png |
| fcf-피쳐-컨트롤-프레임 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g04/gibon-g04-03.png |
| fcf-피쳐-컨트롤-프레임 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g04/gibon-g04-04.png |
| fcf-피쳐-컨트롤-프레임 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g04/gibon-g04-05.png |
| fcf-피쳐-컨트롤-프레임 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g04/gibon-g04-06.png |
| fcf-피쳐-컨트롤-프레임 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g04/gibon-g04-07.png |
| fcf-피쳐-컨트롤-프레임 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g04/gibon-g04-08.png |
| fcf-피쳐-컨트롤-프레임 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g04/gibon-g04-09.png |
| 체계로서의-gdt | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g05/gibon-g05-01.png |
| 체계로서의-gdt | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g05/gibon-g05-02.png |
| 체계로서의-gdt | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g05/gibon-g05-03.png |
| rule-1-실제-적용과-검사방법 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g06/gibon-g06-01.png |
| rule-1-실제-적용과-검사방법 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g06/gibon-g06-02.png |
| rule-1-실제-적용과-검사방법 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g06/gibon-g06-03.png |
| 공차편차오차-기하공차-필수-용어-정리 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g08/gibon-g08-01.png |
| 공차편차오차-기하공차-필수-용어-정리 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g08/gibon-g08-02.png |
| 공차편차오차-기하공차-필수-용어-정리 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g08/gibon-g08-03.png |
| 공차편차오차-기하공차-필수-용어-정리 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g08/gibon-g08-04.png |
| 공차편차오차-기하공차-필수-용어-정리 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g08/gibon-g08-05.png |
| 원페이지-기하공차-1-page-gdt | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g09/gibon-g09-01.png |
| 기하공차-gdt-시작-fcf | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g10/gibon-g10-01.png |
| 기하공차-gdt-시작-fcf | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g10/gibon-g10-02.png |
| 기하공차-gdt-시작-fcf | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g10/gibon-g10-03.png |
| 기하공차-gdt-시작-fcf | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g10/gibon-g10-04.png |
| 베이직-치수-일반-치수-비교 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g11/gibon-g11-01.png |
| 베이직-치수-일반-치수-비교 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g11/gibon-g11-02.png |
| 베이직-치수-일반-치수-비교 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g11/gibon-g11-03.png |
| 베이직-치수-일반-치수-비교 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g11/gibon-g11-04.png |
| 베이직-치수-일반-치수-비교 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g11/gibon-g11-05.png |
| 베이직-치수 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g12/gibon-g12-01.png |
| 베이직-치수 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g12/gibon-g12-02.png |
| 베이직-치수 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g12/gibon-g12-03.png |
| 베이직-치수 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g12/gibon-g12-04.png |
| 베이직-치수의-완전한-이해-개념부터-트루-포지션 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g13/gibon-g13-01.png |
| 베이직-치수의-완전한-이해-개념부터-트루-포지션 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g13/gibon-g13-02.png |
| 베이직-치수의-완전한-이해-개념부터-트루-포지션 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g13/gibon-g13-03.png |
| 베이직-치수의-완전한-이해-개념부터-트루-포지션 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g13/gibon-g13-04.png |
| 베이직-치수의-완전한-이해-개념부터-트루-포지션 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g13/gibon-g13-05.png |
| 베이직-치수의-완전한-이해-개념부터-트루-포지션 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g13/gibon-g13-06.png |
| 베이직-치수의-완전한-이해-개념부터-트루-포지션 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g13/gibon-g13-07.png |
| 베이직-치수의-완전한-이해-개념부터-트루-포지션 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g13/gibon-g13-08.png |
| 사이즈-피쳐 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g14/gibon-g14-01.png |
| 사이즈-피쳐 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g14/gibon-g14-02.png |
| 사이즈-피쳐 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g14/gibon-g14-03.png |
| 사이즈-피쳐 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g14/gibon-g14-04.png |
| 사이즈-피쳐 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g14/gibon-g14-05.png |
| 사이즈-피쳐 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g14/gibon-g14-06.png |
| 사이즈-피쳐의-성립조건 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g15/gibon-g15-01.png |
| 사이즈-피쳐의-성립조건 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g15/gibon-g15-02.png |
| 사이즈-피쳐의-성립조건 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g15/gibon-g15-03.png |
| 사이즈-피쳐의-성립조건 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g15/gibon-g15-04.png |
| 서피스-피쳐-사이즈-피쳐-비교 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g16/gibon-g16-01.png |
| 서피스-피쳐-사이즈-피쳐-비교 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g16/gibon-g16-02.png |
| 서피스-피쳐-사이즈-피쳐-비교 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g16/gibon-g16-03.png |
| 서피스-피쳐-사이즈-피쳐-비교 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g16/gibon-g16-04.png |
| 서피스-피쳐-사이즈-피쳐-비교 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g16/gibon-g16-05.png |
| 서피스-피쳐-사이즈-피쳐-비교 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g16/gibon-g16-06.png |
| 서피스-해석-vs-중심축-해석-측정방법이-다르면-해석 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g17/gibon-g17-01.png |
| 서피스-해석-vs-중심축-해석-측정방법이-다르면-해석 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g17/gibon-g17-02.png |
| 서피스-해석-vs-중심축-해석-측정방법이-다르면-해석 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g17/gibon-g17-03.png |
| 서피스-해석-vs-중심축-해석-측정방법이-다르면-해석 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g17/gibon-g17-04.png |
| 서피스-해석-vs-중심축-해석-측정방법이-다르면-해석 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g17/gibon-g17-05.png |
| 서피스-피쳐-비교 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g18/gibon-g18-01.png |
| 서피스-피쳐-비교 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g18/gibon-g18-02.png |
| 서피스-피쳐-비교 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g18/gibon-g18-03.png |
| 서피스-피쳐-비교 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g18/gibon-g18-04.png |
| 서피스-피쳐-비교 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g18/gibon-g18-05.png |
| 도면에-없으면-없는-것이다 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g19/gibon-g19-01.png |
| 도면에-없으면-없는-것이다 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g19/gibon-g19-02.png |
| 도면에-없으면-없는-것이다 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g19/gibon-g19-03.png |
| 피쳐-정의 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g20/gibon-g20-01.png |
| 피쳐-정의 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g20/gibon-g20-02.png |
| 피쳐-정의 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g20/gibon-g20-03.png |
| 피쳐-정의 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g20/gibon-g20-04.png |
| 피쳐-정의 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g20/gibon-g20-05.png |
| 피쳐-정의 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g20/gibon-g20-06.png |
| 피쳐-정의 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/gibon-g20/gibon-g20-07.png |
| 기하공차-해석-1 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-1/haeseok-1-01.png |
| 기하공차-해석-1 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-1/haeseok-1-02.png |
| 기하공차-해석-1 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-1/haeseok-1-03.png |
| 기하공차-해석-1 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-1/haeseok-1-04.png |
| 기하공차-해석-1 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-1/haeseok-1-05.png |
| 기하공차-해석-1 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-1/haeseok-1-06.png |
| 기하공차-해석-1 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-1/haeseok-1-07.png |
| 기하공차-해석-1 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-1/haeseok-1-08.png |
| 기하공차-해석-1 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-1/haeseok-1-09.png |
| 기하공차-해석-1 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-1/haeseok-1-10.png |
| 기하공차-해석-1 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-1/haeseok-1-11.png |
| 기하공차-해석-1 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-1/haeseok-1-12.png |
| 기하공차-해석-1 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-1/haeseok-1-13.png |
| 기하공차-해석-1 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-1/haeseok-1-14.png |
| 기하공차-해석-1 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-1/haeseok-1-15.png |
| 기하공차-해석-3-원통형-피쳐 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-3/haeseok-3-01.png |
| 기하공차-해석-3-원통형-피쳐 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-3/haeseok-3-02.png |
| 기하공차-해석-3-원통형-피쳐 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-3/haeseok-3-03.png |
| 기하공차-해석-3-원통형-피쳐 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-3/haeseok-3-04.png |
| 기하공차-해석-3-원통형-피쳐 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-3/haeseok-3-05.png |
| 기하공차-해석-3-원통형-피쳐 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-3/haeseok-3-06.png |
| 기하공차-해석-3-원통형-피쳐 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-3/haeseok-3-07.png |
| 기하공차-해석-3-원통형-피쳐 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-3/haeseok-3-08.png |
| 기하공차-해석-4-너비형-피쳐 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-4/haeseok-4-01.jpg |
| 기하공차-해석-4-너비형-피쳐 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-4/haeseok-4-02.jpg |
| 기하공차-해석-4-너비형-피쳐 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-4/haeseok-4-03.jpg |
| 기하공차-해석-4-너비형-피쳐 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-4/haeseok-4-04.jpg |
| 기하공차-해석-4-너비형-피쳐 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-4/haeseok-4-05.jpg |
| 기하공차-해석-4-너비형-피쳐 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-4/haeseok-4-06.jpg |
| 기하공차-해석-4-너비형-피쳐 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-4/haeseok-4-07.jpg |
| 기하공차-해석-4-너비형-피쳐 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-4/haeseok-4-08.jpg |
| 기하공차-해석-4-너비형-피쳐 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-4/haeseok-4-09.jpg |
| 기하공차-해석-5-구형-피쳐 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-5/haeseok-5-01.jpg |
| 기하공차-해석-5-구형-피쳐 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-5/haeseok-5-02.jpg |
| 기하공차-해석-5-구형-피쳐 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-5/haeseok-5-03.jpg |
| 기하공차-해석-5-구형-피쳐 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-5/haeseok-5-04.jpg |
| 기하공차-해석-5-구형-피쳐 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-5/haeseok-5-05.jpg |
| 기하공차-해석-5-구형-피쳐 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-5/haeseok-5-06.jpg |
| 기하공차-해석-5-구형-피쳐 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-5/haeseok-5-07.jpg |
| 기하공차-해석-5-구형-피쳐 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-5/haeseok-5-08.jpg |
| 기하공차-해석-6-mmc-패턴홀 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-6/haeseok-6-01.png |
| 기하공차-해석-6-mmc-패턴홀 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-6/haeseok-6-02.png |
| 기하공차-해석-6-mmc-패턴홀 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-6/haeseok-6-03.png |
| 기하공차-해석-6-mmc-패턴홀 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-6/haeseok-6-04.png |
| 기하공차-해석-6-mmc-패턴홀 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-6/haeseok-6-05.png |
| 기하공차-해석-6-mmc-패턴홀 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-6/haeseok-6-06.png |
| 기하공차-해석-6-mmc-패턴홀 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-6/haeseok-6-07.png |
| 기하공차-해석-6-mmc-패턴홀 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-6/haeseok-6-08.png |
| 기하공차-해석-6-mmc-패턴홀 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-6/haeseok-6-09.png |
| 기하공차-해석-6-mmc-패턴홀 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-6/haeseok-6-10.png |
| 기하공차-해석-6-mmc-패턴홀 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-6/haeseok-6-11.png |
| 기하공차-해석-6-mmc-패턴홀 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-6/haeseok-6-12.png |
| 기하공차-해석-6-mmc-패턴홀 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-6/haeseok-6-13.png |
| 기하공차-해석-6-mmc-패턴홀 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-6/haeseok-6-14.png |
| 기하공차-해석-6-mmc-패턴홀 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-6/haeseok-6-15.png |
| 기하공차-해석-6-mmc-패턴홀 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-6/haeseok-6-16.png |
| 기하공차-해석-6-mmc-패턴홀 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-6/haeseok-6-17.png |
| 기하공차-해석-6-mmc-패턴홀 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-6/haeseok-6-18.png |
| 기하공차-해석-6-mmc-패턴홀 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-6/haeseok-6-19.png |
| 기하공차-해석-6-mmc-패턴홀 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-6/haeseok-6-20.png |
| 기하공차-해석-6-mmc-패턴홀 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-6/haeseok-6-21.png |
| 기하공차-해석-6-mmc-패턴홀 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-6/haeseok-6-22.png |
| 기하공차-해석-6-mmc-패턴홀 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-6/haeseok-6-23.png |
| 기하공차-해석-6-mmc-패턴홀 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-6/haeseok-6-24.png |
| 기하공차-해석-6-mmc-패턴홀 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-6/haeseok-6-25.png |
| 기하공차-해석-6-mmc-패턴홀 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-6/haeseok-6-26.png |
| 기하공차-해석-6-mmc-패턴홀 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-6/haeseok-6-27.png |
| 기하공차-해석-6-mmc-패턴홀 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-6/haeseok-6-28.png |
| 기하공차-해석-6-mmc-패턴홀 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-6/haeseok-6-29.png |
| 기하공차-해석하기-7-6개의-패턴홀 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-7/haeseok-7-01.png |
| 기하공차-해석하기-7-6개의-패턴홀 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-7/haeseok-7-02.png |
| 기하공차-해석하기-7-6개의-패턴홀 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-7/haeseok-7-03.png |
| 기하공차-해석하기-7-6개의-패턴홀 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-7/haeseok-7-04.png |
| 기하공차-해석하기-7-6개의-패턴홀 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-7/haeseok-7-05.png |
| 기하공차-해석하기-7-6개의-패턴홀 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-7/haeseok-7-06.png |
| 기하공차-해석하기-7-6개의-패턴홀 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-7/haeseok-7-07.png |
| 기하공차-해석하기-7-6개의-패턴홀 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-7/haeseok-7-08.png |
| 기하공차-해석하기-7-6개의-패턴홀 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-7/haeseok-7-09.png |
| 기하공차-해석하기-7-6개의-패턴홀 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-7/haeseok-7-10.png |
| 기하공차-해석하기-7-6개의-패턴홀 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-7/haeseok-7-11.png |
| 기하공차-해석하기-7-6개의-패턴홀 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-7/haeseok-7-12.png |
| 기하공차-해석하기-7-6개의-패턴홀 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/haeseok-7/haeseok-7-13.png |
| mmc-검사 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-gauge/jaeryo-gauge-01.png |
| mmc-검사 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-gauge/jaeryo-gauge-02.png |
| mmc-검사 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-gauge/jaeryo-gauge-03.png |
| mmc-검사 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-gauge/jaeryo-gauge-04.png |
| mmc-검사 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-gauge/jaeryo-gauge-05.png |
| 공차재료조건_rfs_mmc_lmc | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-intent/jaeryo-intent-01.png |
| 공차재료조건_rfs_mmc_lmc | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-intent/jaeryo-intent-02.png |
| 공차재료조건_rfs_mmc_lmc | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-intent/jaeryo-intent-03.png |
| 공차재료조건_rfs_mmc_lmc | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-intent/jaeryo-intent-04.png |
| 공차재료조건_rfs_mmc_lmc | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-intent/jaeryo-intent-05.png |
| 공차재료조건_rfs_mmc_lmc | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-intent/jaeryo-intent-06.png |
| 공차재료조건_rfs_mmc_lmc | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-intent/jaeryo-intent-07.png |
| 공차재료조건_rfs_mmc_lmc | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-intent/jaeryo-intent-08.png |
| 사이즈-피쳐의-mmc와-lmc | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-machining/jaeryo-machining-01.png |
| 사이즈-피쳐의-mmc와-lmc | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-machining/jaeryo-machining-02.png |
| 사이즈-피쳐의-mmc와-lmc | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-machining/jaeryo-machining-03.png |
| 사이즈-피쳐의-mmc와-lmc | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-machining/jaeryo-machining-04.png |
| 사이즈-피쳐의-mmc와-lmc | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-machining/jaeryo-machining-05.png |
| 사이즈-피쳐의-mmc와-lmc | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-machining/jaeryo-machining-06.png |
| mmb-계산과-적절한-mmb-선택 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-mmb/jaeryo-mmb-01.png |
| mmb-계산과-적절한-mmb-선택 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-mmb/jaeryo-mmb-02.png |
| mmb-계산과-적절한-mmb-선택 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-mmb/jaeryo-mmb-03.png |
| mmb-계산과-적절한-mmb-선택 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-mmb/jaeryo-mmb-04.png |
| mmb-계산과-적절한-mmb-선택 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-mmb/jaeryo-mmb-05.png |
| mmb-계산과-적절한-mmb-선택 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-mmb/jaeryo-mmb-06.png |
| mmb-계산과-적절한-mmb-선택 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-mmb/jaeryo-mmb-07.png |
| mmb-계산과-적절한-mmb-선택 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-mmb/jaeryo-mmb-08.png |
| mmb-계산과-적절한-mmb-선택 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-mmb/jaeryo-mmb-09.png |
| mmb-계산과-적절한-mmb-선택 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-mmb/jaeryo-mmb-10.png |
| mmb-계산과-적절한-mmb-선택 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-mmb/jaeryo-mmb-11.png |
| mmb-계산과-적절한-mmb-선택 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-mmb/jaeryo-mmb-12.png |
| mmb-계산과-적절한-mmb-선택 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-mmb/jaeryo-mmb-13.png |
| mmb-계산과-적절한-mmb-선택 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-mmb/jaeryo-mmb-14.png |
| 공차조건-모디파이어 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-modifier/jaeryo-modifier-01.png |
| 공차조건-모디파이어 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-modifier/jaeryo-modifier-02.png |
| 공차조건-모디파이어 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-modifier/jaeryo-modifier-03.png |
| 공차조건-모디파이어 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-modifier/jaeryo-modifier-04.png |
| 공차조건-모디파이어 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-modifier/jaeryo-modifier-05.png |
| 공차조건-모디파이어 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-modifier/jaeryo-modifier-06.png |
| mmc-특정재료상태 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-state/jaeryo-state-01.png |
| mmc-특정재료상태 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-state/jaeryo-state-02.png |
| mmc-특정재료상태 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-state/jaeryo-state-03.png |
| mmc-특정재료상태 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-state/jaeryo-state-04.png |
| mmc-특정재료상태 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-state/jaeryo-state-05.png |
| mmc-특정재료상태 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-state/jaeryo-state-06.png |
| mmc-특정재료상태 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jaeryo-state/jaeryo-state-07.png |
| 기하공차-통제목표 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-control-target/jongryu-control-target-01.png |
| 기하공차-통제목표 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-control-target/jongryu-control-target-02.png |
| 기하공차-통제목표 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-control-target/jongryu-control-target-03.png |
| 기하공차-통제목표 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-control-target/jongryu-control-target-04.png |
| 기하공차-통제목표 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-control-target/jongryu-control-target-05.png |
| 기하공차-통제목표 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-control-target/jongryu-control-target-06.png |
| 윤곽공차의-확장-2-범위지정-비트윈-올어라운드-올 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-extent/jongryu-extent-01.png |
| 윤곽공차의-확장-2-범위지정-비트윈-올어라운드-올 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-extent/jongryu-extent-02.png |
| 윤곽공차의-확장-2-범위지정-비트윈-올어라운드-올 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-extent/jongryu-extent-03.png |
| 윤곽공차의-확장-2-범위지정-비트윈-올어라운드-올 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-extent/jongryu-extent-04.png |
| 기하공차-유형-특징 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-five-types/jongryu-five-types-01.png |
| 기하공차-유형-특징 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-five-types/jongryu-five-types-02.png |
| 기하공차-유형-특징 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-five-types/jongryu-five-types-03.png |
| 기하공차-유형-특징 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-five-types/jongryu-five-types-04.png |
| 기하공차-유형-특징 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-five-types/jongryu-five-types-05.png |
| 기하공차-통제속성 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-four-attributes/jongryu-four-attributes-01.png |
| 기하공차-통제속성 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-four-attributes/jongryu-four-attributes-02.png |
| 기하공차-통제속성 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-four-attributes/jongryu-four-attributes-03.png |
| 기하공차-통제속성 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-four-attributes/jongryu-four-attributes-04.png |
| 기하공차-통제속성 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-four-attributes/jongryu-four-attributes-05.png |
| 기하공차-통제속성 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-four-attributes/jongryu-four-attributes-06.png |
| 기하공차-통제속성 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-four-attributes/jongryu-four-attributes-07.png |
| 기하공차-통제속성 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-four-attributes/jongryu-four-attributes-08.png |
| 윤곽공차의-확장-3-불균일한-공차영역의-정의-비트윈 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-nonuniform/jongryu-nonuniform-01.png |
| 윤곽공차의-확장-3-불균일한-공차영역의-정의-비트윈 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-nonuniform/jongryu-nonuniform-02.png |
| 윤곽공차의-확장-3-불균일한-공차영역의-정의-비트윈 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-nonuniform/jongryu-nonuniform-03.png |
| 윤곽공차의-확장-3-불균일한-공차영역의-정의-비트윈 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-nonuniform/jongryu-nonuniform-04.png |
| 윤곽공차의-확장-3-불균일한-공차영역의-정의-비트윈 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-nonuniform/jongryu-nonuniform-05.png |
| 윤곽공차의-확장-3-불균일한-공차영역의-정의-비트윈 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-nonuniform/jongryu-nonuniform-06.png |
| 윤곽공차의-확장-3-불균일한-공차영역의-정의-비트윈 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-nonuniform/jongryu-nonuniform-07.png |
| 윤곽공차의-확장-1-불균등-공차영역을-정의하는-ⓤ-모 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-unequal-u/jongryu-unequal-u-01.png |
| 윤곽공차의-확장-1-불균등-공차영역을-정의하는-ⓤ-모 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-unequal-u/jongryu-unequal-u-02.png |
| 윤곽공차의-확장-1-불균등-공차영역을-정의하는-ⓤ-모 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-unequal-u/jongryu-unequal-u-03.png |
| 윤곽공차의-확장-1-불균등-공차영역을-정의하는-ⓤ-모 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-unequal-u/jongryu-unequal-u-04.png |
| 윤곽공차의-확장-1-불균등-공차영역을-정의하는-ⓤ-모 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/jongryu-unequal-u/jongryu-unequal-u-05.png |
| 자전거로-알아보는-기하공차 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/sijak-ambiguity/sijak-ambiguity-01.jpg |
| 자전거로-알아보는-기하공차 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/sijak-ambiguity/sijak-ambiguity-02.jpg |
| 자전거로-알아보는-기하공차 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/sijak-ambiguity/sijak-ambiguity-03.jpg |
| 자전거로-알아보는-기하공차 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/sijak-ambiguity/sijak-ambiguity-04.jpg |
| 자전거로-알아보는-기하공차 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/sijak-ambiguity/sijak-ambiguity-05.jpg |
| 치수공차의-한계 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/sijak-assembly/sijak-assembly-01.png |
| 치수공차의-한계 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/sijak-assembly/sijak-assembly-02.png |
| 치수공차의-한계 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/sijak-assembly/sijak-assembly-03.png |
| 불량품이-합격하고-양품이-불합격되는-치수공차 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/sijak-defect-pass/sijak-defect-pass-01.png |
| 불량품이-합격하고-양품이-불합격되는-치수공차 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/sijak-defect-pass/sijak-defect-pass-02.png |
| 불량품이-합격하고-양품이-불합격되는-치수공차 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/sijak-defect-pass/sijak-defect-pass-03.png |
| 불량품이-합격하고-양품이-불합격되는-치수공차 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/sijak-defect-pass/sijak-defect-pass-04.png |
| 불량품이-합격하고-양품이-불합격되는-치수공차 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/sijak-defect-pass/sijak-defect-pass-05.png |
| 불량품이-합격하고-양품이-불합격되는-치수공차 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/sijak-defect-pass/sijak-defect-pass-06.png |
| 불량품이-합격하고-양품이-불합격되는-치수공차 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/sijak-defect-pass/sijak-defect-pass-07.png |
| 불량품이-합격하고-양품이-불합격되는-치수공차 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/sijak-defect-pass/sijak-defect-pass-08.png |
| 불량품이-합격하고-양품이-불합격되는-치수공차 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/sijak-defect-pass/sijak-defect-pass-09.png |
| 불량품이-합격하고-양품이-불합격되는-치수공차 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/sijak-defect-pass/sijak-defect-pass-10.png |
| 불량품이-합격하고-양품이-불합격되는-치수공차 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/sijak-defect-pass/sijak-defect-pass-11.png |
| 불량품이-합격하고-양품이-불합격되는-치수공차 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/sijak-defect-pass/sijak-defect-pass-12.png |
| 불량품이-합격하고-양품이-불합격되는-치수공차 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/sijak-defect-pass/sijak-defect-pass-13.png |
| 불량품이-합격하고-양품이-불합격되는-치수공차 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/sijak-defect-pass/sijak-defect-pass-14.png |
| 불량품이-합격하고-양품이-불합격되는-치수공차 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/sijak-defect-pass/sijak-defect-pass-15.png |
| 불량품이-합격하고-양품이-불합격되는-치수공차 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/sijak-defect-pass/sijak-defect-pass-16.png |
| 불량품이-합격하고-양품이-불합격되는-치수공차 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/sijak-defect-pass/sijak-defect-pass-17.png |
| 불량품이-합격하고-양품이-불합격되는-치수공차 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/sijak-defect-pass/sijak-defect-pass-18.png |
| 불량품이-합격하고-양품이-불합격되는-치수공차 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/sijak-defect-pass/sijak-defect-pass-19.png |
| 도면오류비용 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/sijak-legal/sijak-legal-01.png |
| 도면오류비용 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/sijak-legal/sijak-legal-02.png |
| 기하공차로-좌절한-엔지니어를-위한-힐링-자기계발 | https://cdn.jsdelivr.net/gh/charlotteyoon/wp-image@main/posts/sijak-training/sijak-training-01.png |

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
