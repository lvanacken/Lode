---
  title: "Introduction to Lode"
  description: "Let's try to introduce Lode via Python!"
---

## My Personalia

```yaml
type: NormalExercise 
lang: python
xp: 100 
skills: 2
key: 9585a16145   
```


Typically we ask some first things to an individual when we introduce him or her.
Inherently we already know the firstname (Lode) but what is Lode's last name?
What is his gender?


`@instructions`
1.  print `lastname`
2.  print `age`
3.  print `address`

`@hint`
Use print(age)

`@pre_exercise_code`

```{python}
lastname = 'Vanacken'
age = 34
address = 'Diepenbeek'
```

`@sample_code`

```{python}
#print lastname

#print age

#print address
```

`@solution`

```{python}
print(lastname)
print(age)
print(address)
```

`@sct`

```{python}
Ex().has_output(0)
Ex().has_output(1)
Ex().has_output(2)
```
