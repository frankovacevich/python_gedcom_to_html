# python_gedcom_to_html
A simple python script to turn gedcom files to a compact and easy to read html document

I wanted a simple script to plot my family tree. Not beeing able to find one, I created it and uploaded it to this repository.

The code allows you to import a gedcom file and plot it easily as html. Below is an example. You can also use it to plot any tree structure whatsoever, since the gedcom is transformed into a typical tree structure of the form:

```
class t_element:
    name = ""         ## Name displayed
    children = []     ## Vector of t_element (children)
    
    position_x = 0    ## Absolute x position in the html document (to calculate)
    position_y = 0    ## Absolute x position in the html document (to calculate)
   
    def __init__(self, name_, children_):
        self.name = name_
        self.children = children_
```

Hope you find it useful!

![sample](https://raw.githubusercontent.com/frankovacevich/python_gedcom_to_html/master/tree_sample.png)
