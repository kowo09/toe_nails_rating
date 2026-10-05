toe_nail = input("what color is your toe nail?")

match toe_nail:
    case "french toe":
        print ("godess")
    case "black" | "white":
        print ("omg :)")
    case "red"|"yellow" | "blue":
        print ("oh you freaky girl")
    case _:
        print ("what show me a pic!")

