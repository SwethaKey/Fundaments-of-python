# Fundaments-of-python
Style of python programming language  
# 1] Scripting  
    print("Writing Python code in Scripting Way")
    
# 2]Procedural 
    def message():
      print("Procedural")
    message()
    
 # 3]Object Oriented
    class Demo():
      def dish(self):
        print("object oriented")

    d1 = Demo()
    d1.dish()

--------------------------------------------------------------------------------------------------

# IDEL will have two modes:
#  1] Scripting Mode[Python file]
        When ever you writing code in file and saving that file in (.py) that is you used Scripting language
        In script mode, you will write a script and save the scripts with .py extension and then run it.


# 2]Interative Mode[Python Shell]
         if you run you are model in python Shell
         chatting with python in Python Shell is called as int
         Quick calulation and one line activation is called Interactive Mode 
         When you close the python shell. All code will erase
         immediately return thr results of commands when hit enter into the shell

---------------------------------------------------------------------------------------------------

# INDENTATION:
              refers to the spaces at the beginning of a code line.

print("Hello world")
a=10
b=20
d=a+b
print(d)


# Defining The Method
def message():
    print("statement-01")
    name = "tejas"
    print(name)

print("Hello world")
message()



class Demo():
    def dish(self):
        print("Hello world")
        a = 10
        b = 20
        print(a+b)

    print("Hi")

d1=Demo() # Creation of object in python and d1 created adress and hold the ex holding 400 in Heap Segment
d1.dish() # d1 present in stack segment
         
 
