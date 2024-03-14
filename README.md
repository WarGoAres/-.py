# -.py
找出同一天生日
#分化法

#找出同一天生日的人

bir1=[]
bir2=[]




birthday = [316,425,316,723]




for i  in  range(0,2):
  bir1.append(birthday[i])
print(bir1)  

for i in  range(2,4):
  bir2.append(birthday[i])
print(bir2)

bir3=set(bir1)
bir4=set(bir2)
print(bir3 &  bir4)

