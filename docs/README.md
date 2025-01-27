# 우테코 1주차 - 숫자 야구 요구사항 및 기능 정리

## 기본 동작 원리

> 1. 컴퓨터가 세 자리의 Random 값을 생성한다.
> 2. 숫자 야구게임의 시작을 알린다.
> 3. 사용자에게 입력을 요청한다.
> 4. 사용자가 세 자리의 숫자를 입력한다.
> 5. 컴퓨터가 생성한 Random 값과 입력 받은 값을 비교한다.
> 6. 일치하면 정답을 알리며 게임종료를 알린다.
> 7. 일치하면 게임을 다시 시작하거나 완전히 종료할 수 있는 입력을 요청한다.
> 8. 다시 시작을 입력하면 (1을 입력하면 ) 순서 1부터 다시 시작한다.
> 9. 종료를 입력하면 (2를 입력하면) 프로그램이 완전히 종료된다.
> 10. 불일치하면 사용자에게 비교 결과에 대한 힌트를 제공한다.
> 11. 힌트 제공 이후 순서 3부터 다시 시작한다.
> 12. 각종 예외 상황이 발생하면 예외 상황을 알리고 프로그램을 종료한다.

## 구현할 기능 목록 정리

- 세 자리의 Random 값을 생성하는 기능
- 사용자에게 세 자리의 입력받는 기능
- Random 값과 입력 값을 비교하는 기능
- 비교 결과를 출력하는 기능
- 정답일 때, 프로그램 재시작 / 종료를 입력받는 기능
- 프로그램 재시작을 할 수 있는 기능
- 오답일 때, 사용자에게 입력받을 수 있도록 돌아가는 기능
- 예외 상황 발생 시, 예외 케이스를 알리고 프로그램을 종료를 하는 기능

## 예외 상황 정리

- 세 자리 Random 값이 제대로 생성되지 않은 경우
- 사용자가 세 자리 숫자를 입력을 하지 않은 경우
- 사용자가 세 자리 숫자를 입력했지만, 중복되는 숫자를 사용한 경우
- 정답일 때, 1(프로그램 재시작) 또는 2(종료) 이외의 값을 입력하는 경우
- 예외 상황 이외의 예외가 발생하는 경우
