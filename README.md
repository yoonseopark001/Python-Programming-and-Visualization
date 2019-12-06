# Python-Programming



## Exercise

## 1. Print
## 2. Input
## 3. Operators
## 4. If
## 5. For
### Double for loops
## 6. While
## 7. List
## 8. Tuple
## 9. Dictionary
1. input  
```
d = {'one':'111', 'two':'222', 'three':'333'}
```
or
```
d = dict(one = 111, two = 222, three = 333)
```
or
```
x = ['one', 'two', 'three']
y = (111, 222, 333)
z = zip(x, y)
dict(z)
>>> {'one': 111, 'two': 222, 'three': 333}
```

2. load keys

```
d.keys()
>>> dict_keys(['one', 'two', 'three'])
```

3. load values
```
d.values()
>>> dict_values(['111', '222', '333'])
```

```
d['one']
```

```
d.get['one']
>>> 111
```

3. edit  
```
d['one'] = 11111
d
>> {'one': '11111', 'two': '222', 'three': '222'}  
```
4. add
```
d['four'] = '444'
```
or
```
d2 = {}
a = 'Hello'
d2[a] = len(a)
d2
>>> {'Hello' : 5}
```
5. boolean  
```
print('one' in data)
>> true

print('222' in data)
>> false  
```
6. length  
```len(data)
>> 4  
```
7. blank dictionary
```
d2 = dict()
```
8. convert: from list to dictionary
```
dict([['one',1],['two',2]])
>> {'one': 1, 'two': 2}
```
9. convert: tuple to dictionary
```
dict((('one',1),('two',2)))
>>> {'one': 1, 'two': 2}
```
10. convert: to return the list of key and value in tuple
```
d.items()
> dict_items([('one', '11111'), ('two', '222'), ('three', '333'), ('four', '444'])

```
11. loops

```
for k in d.keys():
    print(k, "/", d[k])
>>> one / 11111
    two / 222
    three / 333
    four / 444
```
is the same as
```
for i, j in d.items()
     print(i, '/', j)
>>> one / 11111
    two / 222
    three / 333
    four / 444
```

```
for i in d.items():
    print(i)
>>> ('one', '11111')
    ('two', '222')
    ('three', '333')
    ('three', '444')
```
```
for i in d.items():
    print(i[0])
>>> one
    two
    three
    four
```

```
for i in d.items():
    print(i[0])
>>> 11111
    222
    333
    444
```

