# python-basics
import threading,webbrowser as wb,datetime as dt 
def abd(a):
     print(a)
def cgr(p):
     print(p)
l=[1,2,3,4]
def mnp(a):
     for i in a:
            print(i)
        
mnp(l)

wb.open_new_tab('www.google.com')

a=3
b=8
if(a<b):
        print('trth')
        if(a==b):
            print('ggbth')
        elif(b>a):
            print('dfbfh')
else:
     print('yhnt')
        

l=[1,2,3,4]
if(l==3):
    print('strhj')
elif(l!=3):
        print('trhgj')
else:
        print('sryjdae')
        


f=open('love.txt','w')
f.write('tyh')
f.close()

f=open('love.txt','r')
f.read()


try:
    1/2
    print('true')
except:
    print('dfhnjdty')
finally:
    print('gyhj')


import shshsh
shshsh.x() 

if __name__=='__main__':
            t1=threading.Thread(target=abd,args=(5,))
            t2=threading.Thread(target=cgr,args=(5,)) 


t1.start()
t2.start()
t1.join()
t2.join()


dt.datetime.now()
