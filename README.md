### Description
Create an AGE Calculator that will show your age in years, months, and days with the help of the current date. We will use the ***PyWebIO*** module for creating a simple and interactive interface on the web. This is a python module mostly used to create simple and interactive interfaces on the web using Python programming.

### Installation: 
```python
pip install pywebio
```

### Implementation: 

- Import all the required modules

  ```python
  from dateutil.relativedelta import relativedelta
  from datetime import datetime
  from time import strptime
  from pywebio.input import *
  from pywebio.output import *
  from pywebio.session import *
  import time
  ```
- Split the Birth Date of the user and the Current Date by '/'. And then typecast all the split parts into the integer. Swap months and years for both the user’s birth date and current date.
- Check whether or not the current year is smaller than the User's D.O.B year. If the current year is smaller than through an error.
- Read complete article [**here**](https://www.geeksforgeeks.org/how-to-create-age-calculator-web-app-pywebio-in-python/)

### Output:
![Age](https://user-images.githubusercontent.com/69134468/127765696-853444c4-6790-48f6-9f26-3f1c5be247ae.gif)
