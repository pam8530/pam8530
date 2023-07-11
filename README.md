- 👋 Hi, I’m @pam8530
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
pam8530/pam8530 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
#PYTHON DICT AND LIST TOPIC CODE 
      T1.PY
a = {"key":"values",
     "harry":"coder",
     "marks":"100",
     "colletion":[1,2,9]}

#print(a["colletion"]) # print key respective values
#print(a.items())      # returns all content in dict
#print(a.keys())        #returns key elements in dict



#a.update({"name":"parth"})    #return updated dict
#print(a)

      #                                      sets
#s= set()
#s.add(1)        # Add [1,2,3] in set s
#s.add(2)
#s.add(3)
#print(s)

a = {1,4,3,7,8,10}
#print(len(a))     #retruns the lenght of set a

#a.remove(4)       #remove 4 in sets
#print(a)

#a.pop()            #remvoe random element   
#print(a)

#a.clear()             #remove all elements in set
#print(a)

a.intersection({4,7,3,16,17})
print(a) 



   #T2.PR.SET.PY
myword= {"pustak":"book",
          "kapi":"notebook",
          "vastu":"item",
          "vividh":"diffrent"}
a = input("enetr your hindi word")

myword.get(a)
print("english transation is:",myword.get(a)) 


  #T2.PR2.SET.PY
   num1 = int(input("enetr num1 "))
num2 = int(input("enetr num2  "))
num3 = int(input("enetr num3 " ))
num4 = int(input("enetr num4 " ))
num5 = int(input("enetr num5 " ))
num6 = int(input("enetr num6 " ))
num7 = int(input("enetr num7 " ))
num8 = int(input("enetr num8 " ))
s = ( num1,num2,num3,num4,num5,num6,num7,num8)
print(s)


   #T2.PR3.SET.PY
   MyLang = {}
a = input("enetr fav language shudham: \n  ")
b = input("enetr fav language chinmay: \n  ")
c = input("enetr fav language deep: \n  ")
d = input("enetr fav language gaytree: \n  ")

MyLang["shubham"]=a
MyLang["chinmay"]=b
MyLang["deep"]=c
MyLang["gaytree"]=d

print(MyLang)


