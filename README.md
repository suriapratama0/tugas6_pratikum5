# tugas6Praktikum5


# Membuat Program sederhana input nilai menggunakan Dictionary

	print("PROGRAM INPUT NILAI")
	print("================================")
	While True:
	print("")
	c = input("L)ihat, T)ambah, U)bah, H)apus, C)ari, K)eluar: ")
	if c.lower() == 'l':
   	  break

# Masukan L untuk menampilkan:("Daftar Nilai")

        print("===============================================")
	print("| NO | NIM | NAMA | TUGAS | UTS | UAS | AKHIR |")
	print("===============================================")
	print("			TIDAK ADA DATA		      ")
	print("===============================================")

# Masukan t untuk menampilkan:("Tambah Data")

	print("Tambah Data")
	nilai = []
	nim = input("NIM: ")
	nama = input("NAMA: ")
	nilaiUts = int(input("Nilai UTS: "))
	nilaiUas = int(input("Nilai UAS: "))
	nilaiTugas = int(input("Nilai Tugas: "))
	nilaiAkhir = (nilaiUts * 35/100) + (nilaiUas * 35/100) + (nilaiTugas * 30/100)
   
      nilai.append([nama, nim, nilaiTugas, nilaiUts, nilaiUas, int(nilaiAkhir)])

# Masukan L untuk menampilkan:("Daftar Nilai") yang sudah di tambahkan terlebih dahulu
 
	print("\n	Daftar Nilai	")
	print("===============================================")
	print("| NO | NIM | NAMA | TUGAS | UTS | UAS | AKHIR |")
	print("===============================================")
	
	print("| {no:2d} | {nama:12s} | {nim:9s} | {nilaiTugas:5d} | {nilaiUts:5d} | {nilaiUas:5d} | {nilaiAkhir:6.2f}
	.format(no=i, nim=item[0], nama=item[1], nilaiTugas=item[2], nilaiUts=item[3], nilaiUas=item[4], nilaiAkhir=item[5]))
	print("=============================================================================================================")

		




