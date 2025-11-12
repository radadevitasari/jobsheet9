pertanyaan percobaan 1
1. Jika isi masing-masing elemen array bil diubah dengan angka 5.0, 12867, 7.5, 2000000.
Apa yang terjadi? Mengapa bisa demikian?
Jawab= Program akan error karena array bertipe int, sedangkan nilai 5.0 dan 7.5 bertipe double (ada koma).Java tidak bisa mencampur tipe data berbeda di satu array.Namun, 12867 dan 2000000 tetap bisa karena masih termasuk bilangan bulat (int).

2. Modifikasi kode program di atas dengan melakukan inisialisasi elemen array sekaligus pada saat deklarasi array.

3. Ubah statement pada langkah No 4 menjadi seperti berikut
for (int i = 0; i < 4; i++) 
      { System.out.println(bil(i));
}
Apa keluaran dari program? Jelaskan maksud dari statement tersebut.
Jawab= Program akan error karena cara akses array salah.Java memakai tanda kurung siku [ ], bukan kurung biasa ( ).

4. Jika kondisi pada statement for-loop di atas diubah menjadi: i <= 4, apa keluaran dari program? Mengapa demikian?
Jawab= Program akan error saat dijalankan (ArrayIndexOutOfBoundsException) karena array hanya punya indeks 0–3. Saat i = 4, program mencoba mengambil bil[4] yang tidak ada.Jadi batas loop harus tetap i < 4.

pertanyaan percobaan 2
