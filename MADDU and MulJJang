def main():
    print("안녕하세요! 숫자의 제곱을 계산해 드립니다.")
    
    # 사용자로부터 숫자 입력 받기
    user_input = input("숫자를 입력하세요: ")
    
    try:
        # 입력받은 값을 정수로 변환
        number = int(user_input)
        
        # 제곱 계산
        square = number ** 2
        
        # 결과 출력
        print(f"{number}의 제곱은 {square}입니다.")
        
    except ValueError:
        print("유효한 숫자를 입력해 주세요.")
    
    # 추가 계산 여부 묻기
    while True:
        again = input("다시 계산하시겠습니까? (y/n): ")
        if again.lower() == 'y':
            main()  # 재귀 호출
        elif again.lower() == 'n':
            print("프로그램을 종료합니다. 감사합니다!")
            break
        else:
            print("y 또는 n만 입력해 주세요.")

# 프로그램 시작
if __name__ == "__main__":
    main()
