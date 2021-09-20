# Pertemuan 3

Pada pertemuan ini, membahas tentang _Widget_ dan _Navigation Component_.

## _Widget_

- _Widget_ merupakan komponen utama yang digunakan untuk membagun sebuah UI pada Android.

- _Widget_ merupakan _inheritance_ dari _View class_.

- UI _Widget_ terletak pada _pallete_ di dalam Android Studio.

## _UI Hierarchy_

- Merupakan sebuah hirarki UI yang digunakan untuk membangun sebuah aplikasi android yang terdiri dari sekumpulan _layout_ dan _widgets_.

- Untuk dapat melakukan manipulasi terhadap _widget_ perlu untuk mendefinisikan id didalam XML menggunakan Java ataupun Kotlin.

## _Set/Get Value of Widget_

- Penggunaannya berdasarkan dari _widget_ yang diinisialisasikan.

- Berikut ini komponen _set/get_ dari _widget_ antara lain :

  - EditText: Text etc

  - ImageView: ImageResource etc

  - RadioButton: Text, Checked

  - CheckBox: Text, Checked

## _Navigation Component_

- Navigasi yang dijalankan diantara beberapa layar yang berbeda merupakan salah satu inti utama dari _user experience_ (pengalaman pengguna).

- Komponen Navigasi didesain untuk memastikan bahwa pengguna dapat menerapkan heuristik dan pola yang sama dalam navigasi saat berpindah antar aplikasi.

## _Destination_

- Setiap aplikasi yang dibagun memiliki _start destination_ yang tetap.

- _Destination_ merupakan bagian awal dari aplikasi yang dijalankan oleh user dari _launcher_.

- _Destination_ juga merupakan bagian akhir dari tampilan ketika pengguna menekan tomol kembali.

## _Navigation Graph_

1. _Destination_ merupakan area konten yang berbeda yang terletak pada sebuah aplikasi.

2. _Actions_ merupakan logika yang menghubungkan antara _destination_ yang merepresentasikan _path_ yang bisa digunakan oleh pengguna.

## _Navigation Editor_

1. _Destinations Panel_ merupakan daftar dari _navigation host_ dan semua _destinations_ yang tersedia saat itu juga pada _Graph Editor_.

2. _Graph Editor_ berisi tentang sebuah konten visual yang merepresentasikan dari _navigation graph_. Pengguna dapat berpindah antara _Design view_ dan representasi XML yang mendasari pada tampilan Teks.

3. _Attribute_ berfungsi untuk menunjukkan item _attribute_ yang dipilih di dalam _navigation graph_.

## _Add NavHost into Acivity_

- Salah satu komponen penting dari _Navigation Component_ adalah _Navigation Host_.

- Merupakan sebuah kontainer kosong yang dimana kumpulan _destinations_ ditukar didalam dan diluar sebagai navigasi pengguna melalui aplikasi.

- Host navigasi harus berasal dari _NavHost_.
