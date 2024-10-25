class Talaba:
    def __init__(self,ism,yosh):
        self.ism=ism
        self.yosh=yosh
        self.fanlar=[]
    def f_qosh(self,fan):
        self.fanlar.append(fan)
        return self.fanlar
talaba1=Talaba("Ali",20)
talaba1.f_qosh("Matematika")
talaba1.f_qosh("Kimyo")
print(f"{talaba1.ism}, {talaba1.fanlar}")
