def cal(a,b):
    def add():
        return a+b
    def sub():
        return a-b
    print(add())
    print(sub())
a=int(input("enter a:"))
b=int(input("enter b:"))
cal(a,b)
