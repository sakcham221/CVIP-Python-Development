# CVIP-Python-Development
using the tkinter library for making the GUI calculator
using root as a variable for tkinter
now instead of writing Tk() everywhere we can use root like for giving tittle or geometry(wxl)
taking brics as user input as a string variable
making a frame and store it in the root
and making a function root.mainloop()
and in between root = Tk() and root.mainloop() we having do give every command that we need in the calculator like button , setting frame etc
now we have given all the button's like 1,2,3,4,+,-,/....etc in the calculator according to the style we need we will set the padx and pady for enough space
now we here i am using grid() instead of using pack() because i am positioning the button's by using rows and columns
now bind the button using bind() command and define the function like here i am defing the click as given to each and every button and update your screen
