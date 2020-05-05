def pickingNumbers(a):
      
    m=0
    for i in a:
        c=a.count(i)
        d=a.count(i+1)
        high=c+d
        if(high>m):
            m=high
            
    return m
