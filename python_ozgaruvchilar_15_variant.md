# Python: O‘zgaruvchilar va ma’lumot tiplari — 15 ta variant

Har bir variantdagi kodni o‘qing. Buyruqlar nima vazifa bajarishini, o‘zgaruvchilarning tiplarini va dastur natijasini tushuntiring.

## 1-variant

```python
a = 25
print("Bugun havo yaxshi")
print(a)
print(type(a))

b = str(a)
print(f"Olma shirin {b}")
print(b)
print(type(b))

ism = input("Ismingizni kiriting: ")
print("Tanishganimdan xursandman!")
print(ism)
print(type(ism))
```

## 2-variant

```python
son = "45"
print(f"Kiwi narxi: {son} so‘m")
print(son)
print(type(son))

son = int(son)
print("Endi bu butun son:")
print(son)
print(type(son))

rang = input("Sevimli rangingiz: ")
print(f"{rang} juda chiroyli")
print(type(rang))
```

## 3-variant

```python
harorat = 18.6
print("Ob-havo ma’lumoti")
print(harorat)
print(type(harorat))

harorat = int(harorat)
print(f"Harorat: {harorat} daraja")
print(type(harorat))

shahar = input("Qaysi shahardansiz? ")
print("Xush kelibsiz!")
print(shahar)
print(type(shahar))
```

## 4-variant

```python
a = 12
print("Birinchi qiymat")
print(a)
print(type(a))

b = float(a)
print(f"Natija tayyor: {b}")
print(type(b))

ism = input("Ismingizni yozing: ")
print("Darsni boshlaymiz")
print(ism)
print(type(ism))
```

## 5-variant

```python
matn = "2026"
print("Yangi yil raqami:")
print(matn)
print(type(matn))

yil = int(matn)
print(f"Yil: {yil}")
print(yil)
print(type(yil))

fan = input("Sevimli faningiz: ")
print(f"{fan} juda qiziqarli")
print(type(fan))
```

## 6-variant

```python
narx = "19.5"
print(f"Mahsulot narxi: {narx}")
print(type(narx))

narx = float(narx)
print("Narx son ko‘rinishiga o‘tdi")
print(narx)
print(type(narx))

mahsulot = input("Mahsulot nomini kiriting: ")
print("Buyurtmangiz qabul qilindi")
print(mahsulot)
print(type(mahsulot))
```

## 7-variant

```python
a = 0
print("Boshlang‘ich qiymat")
print(a)
print(type(a))

b = bool(a)
print(f"Tekshiruv natijasi: {b}")
print(type(b))

javob = input("Bugun darsga keldingizmi? ")
print("Javobingiz:")
print(javob)
print(type(javob))
```

## 8-variant

```python
son = "30"
print(f"Qutida {son} ta qalam bor")
print(son)
print(type(son))

son = int(son)
print("Qalamlar soni:")
print(son)
print(type(son))

ism = input("O‘quvchi ismini kiriting: ")
print(f"Omad sizga, {ism}!")
print(type(ism))
```

## 9-variant

```python
a = 7.8
print("Hisoblash boshlanadi")
print(a)
print(type(a))

a = int(a)
print(f"Yaxlitlangan qiymat: {a}")
print(type(a))

son = input("Biror butun son kiriting: ")
print("Siz kiritdingiz:")
print(son)
print(type(son))
```

## 10-variant

```python
holat = True
print("Dastur holati")
print(holat)
print(type(holat))

holat = str(holat)
print(f"Holat matn ko‘rinishida: {holat}")
print(type(holat))

ism = input("Ismingiz: ")
print("Ma’lumot saqlandi")
print(ism)
print(type(ism))
```

## 11-variant

```python
son = "78"
print("Dastlabki qiymat:")
print(son)
print(type(son))

son = float(son)
print(f"O‘nli son: {son}")
print(type(son))

son = int(son)
print("Keyingi qiymat:")
print(son)
print(type(son))

meva = input("Sevimli mevangiz: ")
print(f"{meva} foydali meva")
```

## 12-variant

```python
a = 7.4
b = 2
print("Ikki qiymat bilan ishlaymiz")
print(a)
print(type(a))
print(b)
print(type(b))

a = int(a)
b = float(b)
print(f"Birinchi qiymat: {a}")
print(type(a))
print(f"Ikkinchi qiymat: {b}")
print(type(b))

ism = input("Ismingizni kiriting: ")
print("Ajoyib!")
print(ism)
```

## 13-variant

```python
matn = "56"
print(f"Javonda {matn} ta kitob bor")
print(matn)
print(type(matn))

son = int(matn)
print("Kitoblar soni:")
print(son)
print(type(son))

son = float(son)
print(f"Hisob uchun qiymat: {son}")
print(type(son))

fan = input("Qaysi fanni yoqtirasiz? ")
print(f"{fan} darsi boshlandi")
print(type(fan))
```

## 14-variant

```python
a = 15
b = "20"
print("Ikki o‘zgaruvchini tekshiramiz")
print(a)
print(type(a))
print(b)
print(type(b))

b = int(b)
c = a + b
print(f"Yig‘indi: {c}")
print(c)
print(type(c))

ism = input("Ismingizni kiriting: ")
print("Vazifa yakunlandi")
print(ism)
```

## 15-variant

```python
a = "0"
print("Birinchi tekshiruv")
print(a)
print(type(a))

b = bool(a)
print(f"Matnning mantiqiy qiymati: {b}")
print(type(b))

c = 0
print("Endi sonni tekshiramiz")
print(c)
print(type(c))

c = bool(c)
print(f"Sonning mantiqiy qiymati: {c}")
print(type(c))

son = input("Butun son kiriting: ")
print(f"Siz kiritgan qiymat: {son}")
print(type(son))

son = int(son)
print("Qiymat butun songa o‘zgartirildi")
print(son)
print(type(son))
```

## O‘quvchi bajarishi kerak bo‘lgan topshiriqlar

1. Har bir o‘zgaruvchining qiymatini aniqlang.
2. Har bir o‘zgaruvchining dastlabki va keyingi tipini ayting.
3. `print()` buyruqlari ekranga nimalarni chiqarishini yozing.
4. `input()` orqali kiritilgan qiymatning tipini aniqlang.
5. `str()`, `int()`, `float()` va `bool()` buyruqlari qanday ishlatilganini tushuntiring.
6. Oddiy matn va `f-string` o‘rtasidagi farqni aniqlang.
7. Dasturda xato yuz berishi mumkin bo‘lgan holatlarni toping.
