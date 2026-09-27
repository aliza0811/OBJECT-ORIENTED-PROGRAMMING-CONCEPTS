# OBJECT-ORIENTED-PROGRAMMING-CONCEPTS
**The world of OOP is built on 4 important concepts**. 
1. Class
2. Method
3. Object
4. Function

**Object** is the variable/attributes/properties that stores a data represented by a class. 
**Method** is the action that it performs on the object. 
**Class** is like a blueprint/structure/schema/representation overall containing the methods and objects. 

Class = Object + Method

*A **class** while used in coding is a **Keyword**. A keyword is a reserved built-in word that carries a specific meaning and is used to execute a specific task. A keyword cannot be used as a **Variable**.* 

##Create a class of fruit basket and print the objects that is there inside the basket

#Create a class 
class FruitBasket:  
    def __init__(self,fruitname):    
        self.fruitname=fruitname

#Create Object
A=FruitBasket("Papaya")
B=FruitBasket("Banana")
C=FruitBasket("Apple")
D=FruitBasket("Cherry")

#Print the objects from the basket
print(A.fruitname, B.fruitname, C.fruitname, D.fruitname)
