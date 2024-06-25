t = int(input())
for i in range(0,t):
    x,y = map(int,input().split())
    x+=y
    if(x>=7):
        print("yes")
    else:
        print("no")
        
    
