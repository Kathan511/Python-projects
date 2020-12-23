# Python-projects
->If you want to separate whole words into list then use string.split() method.If you want to separate each letter to list then use for loop.

->To get first digit from int::
def firstDigit(n) : 
  
    # Remove last digit from number 
    # till only one digit is left 
    while n >= 10:  
        n = n / 10; 
      
    # return the first digit 
    return int(n) 
To get last digit from int::
def lastDigit(n) : 
  
    # return the last digit 
    return (n % 10) 
  
