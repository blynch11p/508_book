# Third Chapter

###Keyboard Navigation

Make all interactive elements work with a keyboard. For example, make sure a button that you activate with a click is also in the keyboard tab sequence and that pressing enter or space activates it. Set the tabindex attribute to 0 to add an element to the keyboard tab sequence or set tabindex to -1 so you can use JavaScript to set focus on an element without including it in the tab sequence. We do not recommend using tabindex values greater than 0 even though browsers support them. Note that HTML links and input elements have an implied tabindex of 0.