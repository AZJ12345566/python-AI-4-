# python-AI-4-
python+AI笔记(4)
# 一阶-二章-字符串格式化练习题
name="AI"
stock_price=19.99
stock_code="003032"
factor=1.2
growth_days=7
finally_price=stcok_price*factor**growth_days
print(f"公司：{name},股票代码:{stock_code},当前股价：{stock_price}")
print("每日增长系数：%f,经过%d天的增长后，股价达到了:%.2f" % (factor,grouth_dyas,finally_price))

# 一阶-二章-数据输入(input语句)
#input()函数的内容从键盘中获取
name=input("请告诉我你是谁?")
print("我知道了，你是:%s" % name)

#输入数字类型
num=input("请告诉我你的银行卡：")
print("你的银行卡类型是："type(num))
#输出的类型是字符串，因此用input函数，不管你是什么类型，都会把你的输入类型当作字符串来看待
num=input("请告诉我你的银行卡：")
#数据类型转换
num=int(num)
print("你的银行卡类型是："type(num))
#字符串类型转换成了整形类型

# 一阶-三章-布尔类型和比较运算符
num1=10
num2=10
print(f"10==10的结果是:{num1==num2}")  #返回值是bool类型True

num1=10
num2=15
print(f"1-!=15的结果是:{num1!=num2")  #返回值是bool类型True

#同时还可以进行字符串的比较
name1="itcast"
name2="itheima"
print(f"itcast==itheima结果是:{name1=name2}")

#演示大于小于，大于等于小于等于的比较运算
num1=10
num2=5
print(f"10>5结果是:{num1>num2}")
print(f"10<5的结果是:{num1<num2}")

num1=10
num2=10
pringt(f"10>=10的结果是：{num1>=num2})  #True
pringt(f"10<=10的结果是：{num1<=num2})  #True
#我们可以通过比较运算来得到一个bool值

# 一阶-三章-if语句的基本格式
#python中的if格式不需要加()，但是要加:

# 一阶-三章-成年人判断讲解
age=int(input("请输入你的年龄："))
if age>=18
    print("您已成年，游玩需要买票10元")
print("祝您游玩愉快“)
