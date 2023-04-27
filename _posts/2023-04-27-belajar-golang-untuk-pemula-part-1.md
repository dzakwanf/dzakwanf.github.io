---
layout: post
title: Belajar golang untuk pemula | Part 1
date: 2023-04-27 12:10 +0700
---

# Menuliskan code simple

> untuk mempelajari programing dengan mudah kita harus paham dasar-dasarnya.

Kita akan mencoba program sederhana. Menampilkan `Hallo saya ganteng`.

## 1. Membuat folder tempat code kita

Disini kita akan membuat folder sederhana untuk kode kita ditempatkan.

```bash
mkdir project_saya_ganteng
```

## 2. Menaktifkan depensi untuk tracking code.

Sebelum menulis baris code sederhana. kita perlu mengaktifkan depensi untuk golang terlebih dahulu.

```go
go mod init project/hello_saya_ganteng
```

## 3. Membuat file dengan format .go

Buat file dengan format .go pada direktori kerja

```bash
touch ganten.go
```

## 4. Isikan baris code sederhana

setelah itu kita dapat membuka text editor kita. dan tuliskan bari kode seperti di bawah ini.

```go
package main

import "fmt"

func main() {
    fmt.Println("Halo, saya ganteng 🖐️!")
}
```

## 5. Compile program ke binary code.

setelah selesai menuliskan baris code di langkah ke 4.  langkah selanjutnya kita dapat menjalankan program kita.
dengan perintah di bawah ini.

```bash
go run .
```

**bold ouput**
```go
Halo, saya ganteng 🖐️!
```

