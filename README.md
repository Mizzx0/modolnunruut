# modolnunruut gak work?
Hm apa iya? 

Work apa engga? Tergantung si pembuat file, tujuan bikin file buat cari cuan doang atau emang real mau berbagi.
Jadi logika nya, module non root (file execute) ada yang work ada yang engga.

Konsep kecilnya:
Module root: bakal memodifikasi dan merubah value atau string suatu kode sistem tanpa batas, bahkan bisa memanipulasinya menjadi kode baru.

Module non root: bakal memodifikasi dan merubah value atau string suatu fitur utama android. Contohnya, game driver preference, merubah resolusi, menurunkan ukuran animasi, mematikan beberapa fitur shorcut, membatasi latar belakang, merubah type render.

Perbedaan signifikan yang bisa kita lihat, module root bisa memodifikasi system, kernel, cpu, gpu, i/o bahkan virtual memory hingga kenaikan 200%, sedangkan module non root hanya memodifikasi fitur bawaan android atau kode2 asli android dengan kenaikan 50%.

Contoh kecilnya:
Memasukan kode enable game driver preference di aplikasi brevent, kenapa bisa muncul fitur game driver di opsi pengembang? Padahal non root.

Tytydraco, imlooper dan im_akira beberapa pengembang module magisk yang bikin file non root juga, mereka goblok?
