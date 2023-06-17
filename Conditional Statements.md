Create the following piece of code: If x > 200, print out "Big"; If x > 100 and x <= 200, print out "Average"; and If x <= 100, print out "Small". Use the if, elif, and else keywords in your code.



```python
if x > 200: 
    print ("Big")
elif x > 100 and x <= 200:
    print ("Average")
else:
    print ("Small") 
```

    Average

Keep the first two conditions of the code from the previous exercise (if x > 200, print out "Big"; If x > 100 and x <= 200, print out "Average").

Add a new elif statement, so that, eventually, the program prints "Small" if x >= 0 and x <= 100, and "Negative" if x < 0.

```python
x = 200

if x > 200: 
    print ("Big")
elif x > 100 and x <= 200:
    print ("Average")
    
elif x>=0 and x<=100:
    print("Small")
elif x<0:
    print("Negative")
```

    Average

