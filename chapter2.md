---
title: 'Python Lists Exercises '
description: ''
---

## 2.1. True/False m.c.

```yaml
type: MultipleChoiceExercise
key: c4114ca86b
xp: 50
```

True or False?
A list can contain only integer items.



Special debugging note:
IF YOU HAVE A BUG OF 'SESSION HAS EXPIRED' OR 'SOMETHING WENT WRONG' PLEASE READ THIS [here](https://support.datacamp.com/hc/en-us/articles/360001526593-My-session-keeps-timing-out)

`@possible_answers`
- True
- [False]

`@hint`


`@pre_exercise_code`
```{python}

```

`@sct`
```{python}
msg1 = "Lists are very usefull and they can contain nearly everything, even other lists."
msg2 = "Lists are very usefull and they can contain nearly everything, even other lists."
Ex().has_chosen(correct=2, msgs = [msg1, msg2])
```

---

## 2.2. lists m.c.

```yaml
type: PureMultipleChoiceExercise
key: 0a341f8e76
xp: 50
```

**What is printed by the following statements?**

```
alist = [3, 67, "cat", [56, 57, "dog"], [ ], 3.14, False]
print(alist[2][0])
```

`@hint`
Indexes can be used to access list inside of other lists.

`@possible_answers`
1. 67
2. [c]
3. Error, you cannot have two index values unless you are using slicing.
4. cat

`@feedback`
