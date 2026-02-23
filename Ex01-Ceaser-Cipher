l=list('abcdefghijklmnopqrstuvwxyz')
k=int(input("Enter the key:"))
c=input("Enter Text to be encrypted:").lower()
result=''
for ch in c:
    if ch in l:
        i = l.index(ch)
        ni=(i+k)%26
        result+=l[ni]
    else:
        result += ch
print("The converted Text is:",result)
