# 20180620
celsius = int( input('輸入一個攝氏溫度:'))
fahrenheit = (9/5)* celsius +32
print('華氏溫度:'+fahrenheit)


numA=5
numB=6
if numA <= numB:
    print("numB它是比較大的數字")


S=0
for i in range(0,101,1):
    if i%2 ==0:
        S = S+i
        print("累加和是:",S)


numbers = [100,25,125,50,150,75,175]
for x in numbers:
    print(x)
    if x == 25:
        print("找到了!!!")
        break;
        
        
for i in range(1,11) :
    s=""
    for j in range(0,10-i):
        s +=""
        for j in range(0,2*i-1):
            s +="*"
            print(s)
            
mystr="足球，撞球，羽毛球，桌遊，看書，旅遊，電影，音樂"    
li = mystr.split('，') 
print("該生的愛好有"+str(len(li))+"項")    

x = 20000#本金 20000 元 
years=0
while x < 30000:
    years += 1
    x = x*(1+0.019)    
print(str(years)+"年以後，存款會增加1倍")   
