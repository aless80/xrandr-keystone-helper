xrandr-keystone-helper

This program helps finding the parameters for xrandr --transform.
This can be helpful for setting up [keystone-correction](https://www.projectorpeople.com/resources/keystone-correction.asp) for projectors.

Transformed pictures with "xrandr --tranform" may (very likely) still have some issues especially around the cursor.
The result could be sufficient for viewing movies or presenting slides.

Use Python 3.x and install the dependencies with: 

pip3 install matplotlib --user  

Execution:  
```python3 xrandr-keystone-helper.py```

Adjust the red tetragon/quadrilateral and test the result until you find the right parameters. The string to use with xrandr --transform gets printed to the terminal.

To get the Test button working change the eDP1 to the output you want to configure e.g. VGA1 or HDMI-1.
