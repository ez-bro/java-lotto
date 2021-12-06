# 로또

## 진행 방법

* 로또 요구사항을 파악한다.
* 요구사항에 대한 구현을 완료한 후 자신의 github 아이디에 해당하는 브랜치에 Pull Request(이하 PR)를 통해 코드 리뷰 요청을 한다.
* 코드 리뷰 피드백에 대한 개선 작업을 하고 다시 PUSH한다.
* 모든 피드백을 완료하면 다음 단계를 도전하고 앞의 과정을 반복한다.

## 온라인 코드 리뷰 과정

* [텍스트와 이미지로 살펴보는 온라인 코드 리뷰 과정](https://github.com/next-step/nextstep-docs/tree/master/codereview)

## 🚀 1단계 - 문자열 덧셈 계산기

- 쉼표(,) 또는 콜론(:)을 구분자로, 입력 숫자 반환 기능 구현 (v)
    - 빈 값을 전달하면, 0을 반환해야 한다 (v)
- "\\"와 "\n"사이에 위치하는 문자를 커스텀 구분자로 추가되는 기능 구현 (v)
    - ex: “//;\n1;2;3”과 같이 값을 입력할 경우 커스텀 구분자는 세미콜론(;)이며, 결과 값은 6 (v)
- 문자열 계산기에 숫자 이외의 값 또는 음수를 전달하는 경우 RuntimeException 발생 (v)

## 🚀 2단계 - 로또(자동)

- (UI) 로또 구입 금액을 입력하는 InputView 기능 구현 (v)
- `로또 구입 금액` / `1000` 의 개수만큼 로또 생성 기능 구현 (v)
- (UI) 자동 구매시 배정된 당첨 번호 OutputView 출력 기능 구현 (v)
- (UI) 당첨 번호 입력 InputView 기능 구현 (v)
- (UI) 당첨 통계 및 결과 OutputView 구현 (v)
- 맞춘 번호의 개수 반환 기능 구현 (v)
- 수익률 계산 기능 구현 (v)

## 🚀 3단계 - 로또(2등)

- (UI) 보너스볼 입력 기능 구현 (v)
- 보너스볼 당첨 통계 기능 추가 구현 (v)

## 🚀 4단계 - 로또(수동)

- (UI) 수동 번호 입력 기능 구현 (v)
- 수동 번호 발행 Machine 기능 구현 (v)
- 수동 번호 입력 및 저장 기능 구현 (v)
- 수동 번호 입력 후 남은 금액으로 자동 구매하도록 기능 변경 (v)
- `GameMain` 비즈니스 로직 수정 필요 (LottoTickets 를 합산하는 기능) (v)
- (UI) 수동번호 갯수 출력하도록 UI 기능 변경 (v)
  > 수동으로 3장, 자동으로 11개를 구매했습니다.

- `GameMain` 당첨 통계 데이터, 수동 번호 포함되도록 기능 수정 (v)

