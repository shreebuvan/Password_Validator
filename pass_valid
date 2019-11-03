import re
import sys
def pass1():
    a=input("Enter the password with special characters(&,%,#,@)")
    b=store(a)
    check(a,b)

def store(a):
    b=[]
    for i in a:
        b.append(i)
    return b
def check(a,b):
    for j in b:
        if not((re.match(sc,j)) or (re.match(se,j)) or (re.match(sq,j)) or (re.match(sf,j)) or (re.match(nu,j)) or (re.match(al,j)) or (re.match(AL,j))) :
            print("Special characters allowed are @,#,%,&")
            pass1()
            break
    if(len(a)<5 or len(a)>10):
        print("Enter a password with size[5-10] ")
        pass1()  
    else:
        for i in a:
            if(re.match(nu,i)):
                for j in a:
                    if(re.match(sc,j)):
                      print("Valid Password")
                      sys.exit()
                    elif(re.match(se,j)):
                      print("Valid Password")
                      sys.exit()
                    elif(re.match(sq,j)):
                      print("Valid Password")
                      sys.exit()
                    elif(re.match(sf,j)):
                      print("Valid Password")
                      sys.exit()
                else:
                    print("Invalid Password atleast Special character required")
                    pass1()
                break
            elif(re.match(sc,i)):
                for j in a:
                    if(re.match(nu,j)):
                      print("Valid Password")
                      sys.exit()
                else:
                    print("Invalid Password atleast one number required")
                    pass1()
                break
            elif(re.match(se,i)):
                for j in a:
                    if(re.match(nu,j)):
                      print("Valid Password")
                      sys.exit()
                else:
                    print("Invalid Password atleast one number required")
                    pass1()
                break
            elif(re.match(sq,i)):
                for j in a:
                    if(re.match(nu,j)):
                      print("Valid Password")
                      sys.exit()
                else:
                    print("Invalid Password atleast one number required")
                    pass1()
                break
            elif(re.match(sf,i)):
                for j in a:
                    if(re.match(nu,j)):
                      print("Valid Password")
                      sys.exit()
                else:
                    print("Invalid Password atleast one number required")
                    pass1()
                break
al=re.compile('[a-z]')
AL=re.compile('[A-Z]')
nu=re.compile('\d+')
sc=r"&"
se=r"%"
sq=r"#"
sf=r"@"
b=[]
chk=0
pass1()
