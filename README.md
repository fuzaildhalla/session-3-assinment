# Session 3 Python Assignment

This README contains the exercises and code from `session_3_assinment.ipynb`.

1.using all data types and giving them value and printing the data types of variables.

### Exercise 1

```python
# 1.)

my_name_is = "fuzzail" #string datatype
my_age_is = 21         #integer datatype
my_hieght_is = 178.5   # float datatyp
i_have_netflix = False # boolean datatype
print("my name",my_name_is, "| datatype", type(my_name_is))
print("my age", my_age_is, "| datatype" , type(my_age_is) )
print("my hieght", my_hieght_is, "datatype", type(my_hieght_is))
print("i have netflix", i_have_netflix, "datatype", type(i_have_netflix))
```

### Exercise 2

```python
# 2.)
#  Flipkart-style cart prices
prices = ["199.99", "49", "350.75"]
total_cart_amount = sum(float(price) for price in prices)
print(total_cart_amount)
```

### Exercise 3

```python
# 3)

# CRICKET SCORE SCRIPT(INPUT)

score = int(input("Enter your cricket score: "))

if score >= 50:
    print("Half-century!")
else:
    print("Keep going!")
```

### Exercise 4

```python
score = int(input("Enter your cricket score: "))

if score >= 50:
    print("Half-century!")
else:
    print("Keep going!")
```

### Exercise 5

```python
# 4.) BOOL CONVERTION
is_premium = "True"
is_premium_bool = is_premium == "True"
print(is_premium_bool)
print(type(is_premium_bool))
```
