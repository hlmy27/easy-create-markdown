# **Markdown Syntax Guide**
##### By Muhammad Fadhil Hilmi

**Markdown** adalah cara untuk gaya teks di web. Anda mengontrol tampilan dokumen; memformat kata sebagai Bold atau Italic, menambahkan gambar, dan membuat daftar hanyalah beberapa hal yang dapat kita lakukan dengan Markdown. Sebagian besar, Markdown hanya teks biasa dengan beberapa karakter non-abjad dilemparkan, seperti # atau *.

Ini adalah tampilan atau pembuatan dari Markdown dan kalian dapat gunakan pada Github.

# **Header**
# H1
## H2
### H3
#### H4
##### H5
###### H6
```
Contoh :

# H1
## H2
### H3
#### H4
##### H5
###### H6
```

`#` Tag untuk membuat `<h1>` atau heading 1, semakin banyak `#`, maka size dari heading atau teks tersebut akan semakin kecil.

# **Emphasis**
*Teks Italic*
**Teks Bold**
_Kombinasi **Keduanya**_
```
Contoh :

* Dapat membuat teks menjadi Italic *
_ Dapat membuat teks menjadi Italic _

** Dapat membuat teks menjadi Bold **
__ Dapat membuat teks menjadi Bold __

_ Kalian dapat **Kombinasikan** kedua hal tersebut _
```
# **Strikethrought**
Jika kalian ingin membuat teks seperti ~~ini~~ kalian dapat mencobanya dengan menggunakan **Strikethrought**
```
Kalian dapat menggunakan ~~ini~~ untuk membuat Strikethrought.
```
# **List**
### Unordered List
- Item 1
- Item 2
- Item 3
  - Item 3.1
  - Item 3.2
```
Contoh :

- Item 1
- Item 2
- Item 3
    - Item 3.1
    - Item 3.2
```

### Ordered List
1. Item 1
2. Item 2
3. Item 3
   1. Item 3.1
   2. Item 3.2
```
Contoh : 

1. Item 1
2. Item 2
3. Item 3
    1. Item 3.1
    2. Item 3.2
```

# **Gambar**
Github Logo: ![Alt Text](https://lh3.googleusercontent.com/proxy/tpJxN4PRiRXE81MMBffTNo6YsFnE41ZF-VvV8x1BW5-zDIbnhDtuX5MEM0cNoJvxd3dGcJA7cGrqp5bdhrU9TPKd2WLd0tMKg1lEDNMhik_1aZV3NDohfPo)

```
Contoh:

![GitHub Logo](/images/logo.png)
Format: ![Alt Text](url)
```

# **Links**
[[Github]](https://github.com/hlmy27)
[[Instagram]](https://www.instagram.com/fdhlmi_27/)

```
Contoh :

http://github.com - otomatis!
[GitHub](http://github.com)
```
# **Blockquote**
Hilmi, said :
> " Belajar Git itu mudah, asal ada kemauan dari dalam diri sendiri ! "

```
Contoh :

Kalian, 
> Oke, siap !
```
# **Inline Code**
Kalian dapat menggunakan `<code>` pada baris ini.
```
Contoh : 

Kalian dapat menggunakan `<Inline code>` pada setiap baris atau kalimat.
```
# **Syntax Highlighting**
#### HTML
```
```HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
</head>
    <body>
    </body>
</html>
```

Jika kalian ingin membuat Syntax Highlighting seperti diatas, dapat menggunakan ``` pada awal dan akhir kalimat atau syntax yang ingin di **highlight**.
# **Task List**
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item

```
Contoh : 

- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item
```
# **Tables**
Kalian dapat membuat sebuah tabel dengan menggunakan ```-``` untuk membuat baris, dan kemudian ```|``` untuk membuat sebuah kolom.

Kolom Pertama | Kolom Kedua
------------ | -------------
Item 1 | Item 2
Item 3 | Item 3

```
Contoh :

Kolom Pertama | Kolom Kedua
------------ | -------------
Item 1 | Item 2
Item 3 | Item 3
```

# **Emoji**
Github juga mendukung penggunakan [Emoji](https://help.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax#using-emoji) dan dapat kalian gunakan.
Sumber : [Guide Github](https://guides.github.com/features/mastering-markdown/)