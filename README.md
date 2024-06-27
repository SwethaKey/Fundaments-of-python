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
        1.When ever you writing code in file and saving that file in (.py) that is you used Scripting language
        2.In script mode, you will write a script and save the scripts with .py extension and then run it.


# 2]Interative Mode[Python Shell]
         1.if you run you are model in python Shell
         2.chatting with python in Python Shell is called as int
         3.Quick calulation and one line activation is called Interactive Mode 
         4.When you close the python shell. All code will erase
         5.immediately return thr results of commands when hit enter into the shell

---------------------------------------------------------------------------------------------------

# INDENTATION:
    INDENTATION : refers to the spaces at the beginning of a code line.

        print("Hello world")
        a=10
        b=20
        d=a+b
        print(d)


        def message(): # Defining The Method
            print("statement-01")
            name = "tejas"
            print(name)
        
        print("Hello world")
        message()


        class Demo():
            def dish(self): (self) the default parameter for All the methods inside the class
                print("Hello world") # Present inside the class and inside the method
                a = 10
                b = 20
                print(a+b)
        
            print("Hi")
        
        d1=Demo() # Creation of object in python and d1 created adress and hold the ex holding 400 in Heap Segment
        d1.dish() # d1 present in stack segment
         
 
