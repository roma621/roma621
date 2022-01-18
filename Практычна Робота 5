from tkinter import *

def get_text():
    n = entry.get()
    c = entr1.get()
    b = entr2.get()
    cy = entr4.get()
    c1 = (int(3))
    b1 = (int(2))
    S = (int(n) - (int(c1) * int(c) + int(b1) * int(b))) / int(cy) * 1000
    LABEL2['text'] = round(S,0)

window = Tk()
window.geometry('500x500')

label = Label(window,text="скільки мама вам дала грошей")
label.pack()

entry = Entry(window)
entry.pack()

Label1 = Label(window, text='по скільки гривень кг сахара:')
Label1.pack()

entr1 = Entry(window)
entr1.pack()

label2 = Label(window, text='по скільки гривень кг борошна')
label2.pack()

entr2 = Entry(window)
entr2.pack()

label3 = Label(window, text='по скільки гривень кг цукерок')
label3.pack()

entr4 = Entry(window)
entr4.pack()

button = Button(window, text="нажми шоб узнать скільки мальчик може купити канфет", command=get_text).pack()

LABEL2 = Label(window, text='')
LABEL2.pack()

window.mainloop()


n = input("скільки мама вам дала грошей:")
#c = input("по скільки гривень кг сахара:")
#c1 = (int(3))
#b = input("по скільки гривень кг борошна:")
#cy = input("по скільки гривень кг цукерок")
#b1 =(int(2))
#S = (int(n)-(int(c1)*int(c)+int(b1)*int(b)))/int(cy)*1000
#print(round(S, 0))





