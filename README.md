---
layout: challenge
title: Tree Grove
---

## Learning Competencies

* Pemodelan sistem dengan object atau class
* Menggunakan class dan object di JavaScript
* Menggunakan instance variables dan accessor methods secara efektif
* Menggunakan inheritance di JavaScript
* Menggunakan class dari file terpisah (module exports dan require)

## Prerequisite

Untuk dapat mengerjakan challenge ini pastikan kamu sudah mengerjakan challenge mango tree sampai release 2 sudah berhasil membuat class tree baru yang di extends dari class FruitTree.

## Summary
Setelah membuat aplikasi emulator pohon mangga. Mari kita membuat emulator Taman. Kita akan melanjutkan dari pekerjaan tantangan kamu di `Mango Tree`.

### Release 0 : Create a `TreeGrove` Class

Ayo tanam pohon-pohon biar dunia lebih hijau! Buat class dengan nama `TreeGrove` yang dapat melakukan hal-hal berikut:

1. Inisialisasi class `TreeGrove`
2. Ada method `inputTree()` pada class `TreeGrove` yang digunakan untuk memasukkan data pohon saat ini, yang menerima jenis pohon apapun dan umur pohon berapapun.
3. Ada method `showAges()` pada class `TreeGrove` yang akan memberi tahu kita umur setiap pohon yang ada di taman tersebut.
4. Ada method `showTrees()` yang akan me-*return* semua nama pohon yang ada di taman.
5. Ada method `showMatureTrees()` yang akan me-*return* semua nama pohon yang sedang berbuah.
6. Dan ada method `showDeadTrees()` yang akan me-*return* nama-nama pohon yang mati di taman tersebut.

Berikut contoh driver code nya :

```
var grove = new TreeGrove()
// input your trees data !
// parameter ke-1: nama pohon
// parameter ke-2: umur pohon ketika ditanam di taman tersebut
// pamareter ke-3: tinggi pohon pertama kali ketika ditanam di taman tersebut
// parameter ke-4: umur mature pohon tersebut
// parameter ke-5: healthyStatus dari pohon tersebut ketika ditanam
grove.inputTree("MangoTree", 3, 1.8, 7, true)
grove.inputTree("MangoTree", 5, 2.4, 12, true)
grove.inputTree("AppleTree", 4, 1.2, 5, true)
grove.inputTree("PearTree", 7, 2, 15, true)

// next year
grove.nextYear()

// show trees ages
grove.showAge()

// show trees
grove.showTrees()

// show trees
grove.showMatureTrees()

// show trees
grove.showDeadTrees()
```
