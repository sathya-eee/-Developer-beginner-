# -Developer-beginner-
Coding 
stock_list=[]
stock_count=0

print("welcome to digitalstock_book")
print("type  exit is a name of finish\n")
while True:
    name=input("Enter the stock name:")
    if name.lower()=="exit":
        break
    size=input("Enter the stick size:")
    num=int(input("Number of stock:"))
    stock_detail=f"{name},(size:{size}),(num:{num})"
    stock_list.append(stock_detail)
    stock_count+=1
    print(f"succesfully added,{name}!\n")
print("\n____stock_book    summary____")
print(f"total stock today :{stock_count}")
print("stock_list")
for  stock in stock_list:
    print(f"-{stock}")
print("_________________________")
