# as
# 1
nums = [4, 1, 4, 2, 1, 5]
print(set(nums))

# 2 
termins = set()
termins.add("phyton")
termins.add("linux")
termins.add("phyton")
print(len(termins))

# 3
tekshir = input("Meva nomini kiriting: ")
mevalar = {"olma", "nok", "uzum"}
if tekshir in mevalar:
    print("Meva bor")
else:
    print("Meva mavjud emas")

# 4
a = {}
b = set()
c = {1, 2}
print(type(a))
print(type(b))
print(type(c))

# 5
fruits = set()
fruits.add("olma")
print(fruits)

# 6
sinf_a = {"Ali", "Vali", "Laylo"}
sinf_b = {"Laylo", "Sardor", "Ali"}
sets = (sinf_a | sinf_b)
print(len(sets))

# 8
mehmon = ["Ali", "Vali", "Ali", "Laylo", "Vali", "Madina"]
print(set(mehmon))

# 9
word = input("So'z kiriting: ")
word2 = sorted(set(word.lower()))
print(len(word2), 'ta harf', word2)
