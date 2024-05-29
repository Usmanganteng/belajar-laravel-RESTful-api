<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

# Requirement/Persyaratan

## Php versi 8.1
- Cara menginstal php dalam bahasa indonesia : <a href="https://youtu.be/Uw3ZGIMvIdA?si=mBVZ-lBnoCilASzo"> install php

## Laravel versi 10.2.5
- cara menginstal laravel yang versi yang sama : 
```
composer create-project laravel/laravel=v10.2.5 belajar-laravel-RESTful-api
```
---
# Cara Menjalankan/Run

- cd belajar-laravel-RESTful-api

- npm install

# Materi/Pembahasan

## Apa itu API
- RESTful API adalah jenis API (Application Programming Interface) yang menggunakan prinsip REST (Representational State Transfer) untuk memungkinkan komunikasi antara berbagai sistem perangkat lunak melalui HTTP. RESTful API sering digunakan untuk mengakses dan mengelola sumber daya di web.

- Berikut adalah beberapa konsep utama dalam RESTful API:

    1 . Resource (Sumber Daya): Setiap elemen yang dapat diakses atau dimanipulasi oleh API dianggap sebagai sumber daya. Sumber daya ini diidentifikasi oleh URL (Uniform Resource Locator).

    2 . HTTP Verbs (Kata Kerja HTTP): RESTful API menggunakan metode HTTP untuk mengoperasikan sumber daya. Metode yang paling umum digunakan adalah:

    - GET: Untuk mengambil data dari server.

    - POST: Untuk mengirim data ke server dan biasanya digunakan untuk membuat sumber daya baru.

    - PUT: Untuk memperbarui sumber daya yang ada di server.

    - DELETE: Untuk menghapus sumber daya dari server.

    3 . Stateless (Tanpa Keadaan): Setiap permintaan dari klien ke server harus berisi semua informasi yang diperlukan untuk memahami dan memproses permintaan tersebut. Server tidak menyimpan konteks apapun dari permintaan sebelumnya.

    4 . Uniform Interface (Antarmuka Seragam): RESTful API harus memiliki antarmuka yang konsisten dan standar yang memungkinkan interaksi yang mudah antara sistem yang berbeda. Ini termasuk:

    - Identifikasi sumber daya melalui URL.

    - Manipulasi sumber daya melalui representasi yang diwakili (seperti JSON atau XML).

    - Penggunaan standar HTTP methods (GET, POST, PUT, DELETE).

    5 . Client-Server Architecture (Arsitektur Klien-Server): Klien dan server harus saling terpisah sehingga masing-masing dapat dikembangkan dan diskalakan secara independen.

    6 . Cacheable (Dapat Di-cache): Respons dari server dapat di-cache oleh klien untuk meningkatkan performa dan efisiensi.

## belum selesai
