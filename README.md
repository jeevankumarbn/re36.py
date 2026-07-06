
class mobile:
    def __init__(self,Brand,Cost):
        self.Brand = Brand
        self.Cost = Cost

    def Select(self):
        print(f"{self.Brand} offers really good value for money.")


a = mobile("Apple",80000)
b = mobile("Samsung",60000)

a.Select()
b.Select()
