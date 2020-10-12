# fun-gameimport emoji
print("hello,welcome to the game")
player1 = input("enter yor name:")
if (player1>="a" and player1<="z") or (player1>="A" and player1<="Z"):
    print(player1,(" "))
else:
    print("pls, enter your name")
player2 = int(input("enter a number between 1 to 10:"))
if player2>10: 
    print(" you entered invalid number")
else:
    print("you entered correct number")
    if player2==1:
        print(player1,"cutiest")
        print('\U0001F60A')	
    if player2==2:
        print(player1,"foodie")
    if player2==3:
        print(player1,"cunning fellow")
    if player2==4:
        print(player1,"Beautiful")
    if player2==5:
        print(player1,"Charm")
    if player2==6:
        print(player1,"joyel")
    if player2==7:
        print(player1,"sensitive")
    if player2==8:
        print(player1,"deep thinker")
    if player2==9:
        print(player1,"possesive")
    if player2==10:
        print(player1,"angry bird")
    else:
        print("thank you")


