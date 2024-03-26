import random

# 生成随机的for循环
random_list = [random.randint(1, 10) for _ in range(10)]
for num in random_list:
    print(num)

# 生成随机的while循环
count = 0
while count < 10:
    print(count)
    count += 1
