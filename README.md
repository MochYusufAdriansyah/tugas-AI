
# Latihan 1
int_var = 8
float_var = 3.3
string_var = "Hello Python"
list_var = [1, 2, 3, 4, 5]

print("Data Integer : ", int_var)
print("Data Float : ", float_var)
print("Data String : ", string_var)
print("Data List : ", list_var)

#Latihan 2
belanja = ["beras", "minyak", "telur"]
belanja.append("gula")
belanja.append("kopi")

print("\nDaftar belanja:")
for item in belanja:
    print("-", item)
    
#Latihan 3
harga = {
    "beras": 12000,
    "minyak": 17000,
    "telur": 24000,
    "gula": 15000,
    "kopi": 20000
}

total = sum(harga.values())
print("\nTotal harga belanja:", total)

#Latihan 4
r = 7
luas = 3.14 * r * r
keliling = 2 * 3.14 * r

print(f"\nLingkaran jari-jari {r}: luas={luas}, keliling={keliling}")

#Latihan 5
usia = int(input("\nMasukkan usia: "))
if 0 <= usia <= 13:
    print("Anak")
elif 14 <= usia <= 24:
    print("Remaja")
elif 25 <= usia <= 49:
    print("Dewasa")
elif usia >= 50:
    print("Lansia")
else:
    print("Usia tidak valid")
