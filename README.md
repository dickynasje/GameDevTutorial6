# Implementasi
## Implementasi Fitur New Game
Implementasi Tombol New Game menggunakan Link Button yang diposisikan sebagai child dari sebuah container yang menentukan posisi tombol label tersebut di User Interface. Kemudian untuk memberikan sebuah responds ketika seorang user menekan tombol menggunakan script yang kemudian diberikan signal pressed() untuk memberikan sebuah trigger yang perlu dilakukan agar script tersebut jalan, di kasus ini script yang dijalankan adalah melakukan load ke Level 1
## Implementasi Fitur Stage Select
Implementasi ini diawali dengan membuat scene baru yang bekerja sebagai UI dan memberikan info level yang ada. Di dalamnya menggunakan `Margin Container` lalu menjadikan GridContainer sebagai child dari `Margin Container` setelah itu memasukkan dua `Center Container` sebagai tempat untuk menaruh `Link Button` yang kemudian di modifikasi dari fitur sebelumnya(new game button) agar melakukan load scene sesuai level yang ada.
## Implementasi Game Over Button
Implementasi untuk fitur ini cukup mudah, hanya melakukan modifikasi kecil dari tutorial yang ada dengan menambahkan link button yang mengarahkan player kembali ke main menu.

Referensi Yang digunakan:
https://csui-game-development.github.io/tutorials/tutorial-6/#membuat-containers-labels-dan-buttons
