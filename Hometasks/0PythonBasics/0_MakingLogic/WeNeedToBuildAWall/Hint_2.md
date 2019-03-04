# Подсказки

- Вечный цикл в Python можно записать как `while(True)`. Если потребуется выйти из цикла стоит воспользоваться оператором `break`. То есть для код будет похож на код ниже. Нетрудно понять, что результатом программы будет 10

```Python
counter = 0
while(True):
	if counter > 9:
		break
	counter += 1
print(counter)
```

- Для случая с паролем нам потребуется цикл `for`

```Python
for current_try in range(3):
	if current_try == 3:
		break 
```

