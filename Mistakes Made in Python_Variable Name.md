## Mistake

One variable name in Excel is 'Name ', with a space, but it's hard to notice. When I was performing regression, I included the variable 'Name', but it kept giving an error, saying "Name is not defined". I was confused at first because it seemed exactly the same, and `df.info()` also showed it the same way.

## Solution

Later, I used `print(df.columns)` and found that there was a space after 'Name'. Then I rename the variable to the one without a space. 
