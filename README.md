a1 = {
        "imie":"Adam",
        "nazwisko":"Kaminski",
        "hobby":"jedzenie",
        "wzrost" : 189,
        "waga" : 78,
        "kolor_wlosow": "blond",
},

print(f'{a1}')
print(a1["wzrost"])
print(a1["hobby"])

print(a1["waga"])
for i in range(len(a1["waga"])):
    a1["waga"].pop(0)
print(a1["waga"])
a1["waga"] = []
print(a1["waga"])
