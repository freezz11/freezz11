from tkinter import Tk, Label

# Create the main window (hidden initially)
window = Tk()
window.title("The Big Question...")  # Set a title for the window
window.withdraw()  # Hide the window at first

# Define your proposal message
message = "Will you be my wife?"

# Create a label with the message and customize font/size
label = Label(window, text=message, font=("Arial", 36, "bold"), fg="red")                  
label.pack()  # Pack the label into the window

# Make the window appear and keep it open
window.deiconify()
window.mainloop()
