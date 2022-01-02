# Stanislav Semenov

On the way to Full-stack Developer

---

## My contacts

**Phone:** +79212923100

**Telegram:** @asternem

**E-mail:** asternem@gmail.com

---

## Briefly about myself

---

## My skills

- Python
- Django
- HTML
- CSS
- JavaScript
- C#

- Git/GitHub
- Linux (Ubuntu, Debian, CentOS)
- Windows
- Unix (MacOS, FreeBSD)

---

## Code examples

The code example is taken from course "Поколение Python": курс для начинающих on Stepik:

```Python #Панграммы
# объявление функции
def is_pangram(text):
    alphabet = ['a', 'b', 'c', 'd', 'e', 'f', 'g', 'h', 'i', 'j', 'k', 'l', 'm', 'n', 'o', 'p', 'q', 'r', 's', 't', 'u', 'v', 'w', 'x', 'y', 'z']
    count = 0
    txt = []

    for c in text.lower():
        if c.isalpha():
            txt.append(c)

    for c in txt:
        if c in alphabet:
            count += 1
            alphabet.remove(c)

    if count == 26:
        return True
    else:
        return False

# считываем данные
text = input()

# вызываем функцию
print(is_pangram(text))
```

---

## Experience

## Education

### Courses

- **Stepik**  

[![My certificate on Stepik]()](https://stepik.org/cert/877676)

- **RSSchool**  
  JavaScript/Front-end 2021Q3

## English language

Level А2
