userInput = input("Username : ")

passwordIn = input("Password : ")

if userInput == "admin" and passwordIn == "1234" :

    print("----Welcome----")
    
    print("1.Bread 20 THB")
    
    print("2.Water 10 THB")
    
    Userselect = int(input("สินค้าที่ต้องการ : "))
    
    if Userselect == 1:
    
        eabread = int(input("จำนวนขนมปัง :"))
        
        print(eabread * 20,"บาท")
        
    elif Userselect == 2:
    
            eawater = int(input("จำนวนน้ำ :"))
            
            print(eawater * 10,"บาท")



