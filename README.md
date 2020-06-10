# Eiffel2
Neural Network architecture  Visualization tool




## You can use eiffel, which you can install using pip:

 python -m pip install eiffel 

Just import builder from eiffel and provide a list of neurons per layer in your network as an input.

# Example:

from eiffel import builder

builder([1, 10, 10, 5, 5, 2, 1])
# or the following if you want to have a dark theme
 builder([1, 10, 10, 5, 5, 2, 1], bmode="night")
