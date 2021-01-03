# Python-projects
->If you want to separate whole words into list then use string.split() method.If you want to separate each letter to list then use for loop.

->To get first digit from int::
def firstDigit(n) : 
  
    # Remove last digit from number 
    # till only one digit is left 
    while n >= 10:  
        n = n // 10; 
      
    # return the first digit 
    return int(n) 
To get last digit from int::
def lastDigit(n) : 
  
    # return the last digit 
    return (n % 10) 
  
->IF you want to sort list than type (List  name).sort() and if you want to sort string than type sorted((String name)).Sorted function will sort Each character into list type.If you want to refer Anagram Program.You can also use sorted function in List.
