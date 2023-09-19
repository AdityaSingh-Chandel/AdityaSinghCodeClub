# AdityaSinghCodeClub
# Python Method OVERRIDING
class Aditya:
    def __init__(self,a):
        self.a = a

        def Display(self):
            print(self.a," is friend of Aditya")

class Club(Aditya):
    def __init__(self,b):
        self.b= b

        def Display(self):
            print(self.b,"Overrides")

obj1=Aditya(Man)
obj2=Club(Boy)

obj1.Display()
obj2.Display()
