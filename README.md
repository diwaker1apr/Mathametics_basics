# Mathametics_basics
basic mathematics formulas
# trying to create basic mathematics 
# how to get circumference of a cicle when radius is given
class Circle:
    pi =3.14
    def __init__(self,radius=1):
        self.radius = radius
        # area of a circle is 2pir2
        self.area =radius*radius*self.pi
    def get_circumference(self):
        return self.radius*self.pi*2
