# x-dialogs-js

README, please!

1. Introduction

To create a dialog, first, you must have loaded the CSS and JS files.

2. Create a dialog

The philosophy of this library is to keep things simple as hell. So, if you explore the code, you will se that files doesn't exceed of 100 lines any of them. Change what you want, they are there for that.

The JS file only loads one object, which has only 2 methods and no properties.

The object loaded is: 

  xDialogs
  
The first method, to create dialogs, is this one:

  xDialogs.create("Title of the dialog", "<b class="text-dialog">Content of the dialog</b>", {
    "b.text-dialog": function() {
      alert("if you clicked to the text of the dialog, you got this popup");
      xDialogs.closeDialogs();
      alert("And as you see, the dialogs get closed. So simple!");
    }
  });
  
If you understood the example, you see how simple it is to use this library. So, enjoy customizing your own responsive dialogs!










