# Penggunaan Kata Kunci const dan let

• Kata kunci let itu seperti kata kunci var, dimana data di variable tersebut bisa diubah-ubah sesuka kita

• Sedangkan kata kunci const berbeda, ketika sebuah variable sudah diisi di variable const, maka variable tersebut tidak bisa diubah lagi value nya

• Variable sejenis ini kadang dibilang juga constant

## Contoh Sederhana

```javascript
// Menggunakan const - tidak bisa diubah
const nama = "John";
console.log(nama);

// nama = "Jane"; // Error! Tidak bisa mengubah const

// Contoh const untuk angka
const umur = 25;
console.log("Umur: " + umur);

// Contoh const untuk konstanta matematika
const PI = 3.14159;
console.log("Nilai PI: " + PI);
```

**Output:**
```
John
Umur: 25
Nilai PI: 3.14159
```
