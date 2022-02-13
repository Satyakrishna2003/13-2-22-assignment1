# 13-2-22-assignment1
R=100
M=500
W=600
RC=75
SC=90
cname=input('enter customer name:')
cphno=int(input('enter customer phone number:')) 
Rq=int(input('enter number of ravva packets:'))
Mq=int(input('enter number of maida packets:'))
Wq=int(input('enter number of wheat packets:'))
RCq=int(input('enter number of rice packets:'))
SCq=int(input('enter number of sweetcorns:'))
bill=(R*Rq)+(M*Mq)+(W*Wq)+(RC*RCq)+(SC*SCq)
if bill>5000:
   disc=bill*10/100
elif bill>3000:
   disc=bill*8/100
elif bill>2000:
   disc=bill*5/100
elif bill>1000:
   disc=bill*3/100
if bill>3000:
   tax=bill*10/100
else:
   tax=bill*18/100
mainbill=bill-disc+tax
print('bill amount main bill:', mainbill)


OUT PUT
enter customer name:Satya
enter customer phone number:998877445566
enter number of ravva packets:4
enter number of maida packets:6
enter number of wheat packets:2
enter number of rice packets:8
enter number of sweetcorns:4
bill amount main bill: 5560.0
