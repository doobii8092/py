# py
Dictonary problem

#Wap to have a list and delete all the elements from dictonary  whose value is 5

#Method 1
'''
d={'a':2,'b':5,'c':4,'d':5,'e':6,'f':5}
d1={}
print('Dictonary     :,d)
for x in d:
    if (d[x]!=5):
        d1[x]=d[x]
d1 d = d d1
print('New_Dictonary :', d1)
'''

#Method 2
'''
d={'a':2,'b':5,'c':4,'d':5,'e':6,'f':5}
print('Dictonary             :',d)
l=list(d)               # Dictonary to list "l=list(d)" 

l1=[x for x in l if d[x]!=5]          #Storing keys in list
l2=[d[x] for x in l if d[x]!=5]        #storing values in list
d=dict(zip(l1,l2))                # list to dictonary "d=dict(zip(keys,values))"

print('Values after update   :',l2)
print('Keys after update     :',l1)
print('Updated_Dictonary     :',d)
'''
