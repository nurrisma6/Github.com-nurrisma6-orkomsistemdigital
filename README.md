MULAI

  INPUT desimal

  JIKA desimal < 0 MAKA
    TAMPILKAN "Bilangan >= 0"

  ELIF desimal = 0 MAKA
    TAMPILKAN "0 dalam biner adalah 0"

  SELAIN ITU
    angka = desimal
    biner = ""

    SELAMA angka > 0 LAKUKAN
      hasilBagi = angka DIV 2
      sisa = angka MOD 2
      biner = GABUNGKAN(sisa, biner)
      angka = hasilBagi
    SELESAI SELAMA

    TAMPILKAN "Bilangan Desimal: ", desimal
    TAMPILKAN "Bilangan Biner: ", biner

  SELESAI KONDISI

SELESAI
