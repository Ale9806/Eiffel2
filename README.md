# Eiffel2
Neural Network architecture  Visualization tool




## You can use eiffel, which you can install using pip:
```python
python -m pip install ieffel2
 ```
 to update eiffel:
 ```python
python -m pip  install ieffel2 --upgrade
 ```

Just import builder from eiffel and provide a list of neurons per layer in your network as an input.

## Example:
```python
from eiffel2 import builder
builder([1, 10, 10, 5, 5, 2, 1])
# or the following if you want to have a dark theme
builder([1, 10, 10, 5, 5, 2, 1], bmode="night")
```
**output:** (normal mode)

<a href="url"><img src="https://github.com/Ale9806/Eiffel2/blob/master/eiffel2.PNG" align="left"  width="400"  > </a>

<br />&nbsp;<br />
<br />&nbsp;<br />
<br />&nbsp;<br />
<br />&nbsp;<br />



**output:** (with bmode="night')

<a href="url"><img src="https://github.com/Ale9806/Eiffel2/blob/master/eiffel.PNG" align="left"  width="400"  > </a>

<br />&nbsp;<br />
<br />&nbsp;<br />
<br />&nbsp;<br />
<br />&nbsp;<br />
<br />&nbsp;<br />
<br />&nbsp;<br />


**COLORS:**

You can add colors to your network net_colors variable in **builder()** , keep in mind that for a n layer network you 
must select n-1 colors
Eiffel2 is compatible with vanila python colors ("red","blue") and Hex colors 

[Online Color tool](https://www.w3schools.com/colors/colors_picker.asp)

## EXAMPLE
```python
from eiffel2 import builder
builder([1,6,6,5,2],net_colors=["#581845","#900C3F","red","#FF5733"])
```
