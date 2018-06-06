# 5.4
def movavg(lst,k):
    x=len(lst)-k+1
    y=[]
    for i in range(x):
        sum=0
        for j in range(k):
            sum +=lst[i+j]
        z=sum/k
        y.append(int(z))
    print(y)
    
lst1=[3, 5, 7, 2, 8, 10, 11, 65, 72, 81, 99, 100, 150,200]
movavg(lst1,3)
