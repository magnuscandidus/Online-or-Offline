# Online-or-Offline
# cook your dish here
t=int(input())
while t:
    n,m=map(int,input().split())
    a=n-(0.1*n)
    if(a>m):
        print("DINING")
    elif(m>a):
        print("ONLINE")
    else:
        print("EITHER")
    t-=1
    
    
