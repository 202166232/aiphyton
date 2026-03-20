coffee_price = 2000
latte_price = 3000
greentea_price = 2500
juice_price = 2000

total_price = 0


print("\n주문할 메뉴의 수량을 입력해주세요 (0개는 입력할 수 없습니다):")

        coffee_quantity = int(input("커피 몇 개? "))
       
        latte_quantity = int(input("라떼 몇 개? "))
       
        greentea_quantity = int(input("녹차 몇 개? "))
      
        juice_quantity = int(input("주스 몇 개? "))
       

total_price = (coffee_price * coffee_quantity) + \
              (latte_price * latte_quantity) + \
              (greentea_price * greentea_quantity) + \
              (juice_price * juice_quantity)

print("\n--- 주문 내역 ---")
print(f"커피: {coffee_quantity}개")
print(f"라떼: {latte_quantity}개")
print(f"녹차: {greentea_quantity}개")
print(f"주스: {juice_quantity}개")
print(f"총 주문 금액: {total_price}원")
