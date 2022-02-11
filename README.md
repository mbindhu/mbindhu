sno=int(input('enter sno'))
sname=input('enter name')
sgroup=input('enter group')
s1=int(input('s1 marks'))
s2=int(input('s2 marks'))
s3=int(input('s3 marks'))
s4=int(input('s4 marks'))
s5=int(input('s5 marks'))
s6=int(input('s6 marks'))
total=s1+s2+s3+s4+s5+s6
avg=total/6
if avg>91:
    print('O-grade')
elif avg>=81:
    print('A-grade')
elif avg>=71:
    print('B-grade')
elif avg>=60:
    print('C-grade')
elif avg>=50:
    print('D-grade')
elif avg>=40:
    print('pass')

output
enter sno27
enter namehimabindhu
enter groupmccs
s1 marks75
s2 marks74
s3 marks75
s4 marks75
s5 marks74
s6 marks75
B-grade

enter sno27
enter namehima
enter groupmccs
s1 marks100
s2 marks99
s3 marks100
s4 marks100
s5 marks100
s6 marks100
O-grade
>>> 
