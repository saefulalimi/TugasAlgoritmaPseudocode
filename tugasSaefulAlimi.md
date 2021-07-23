#Tugas Algoritma dan Pseudocode

#Project 01
    Deklarasi var:
        - menyiapkan sebuah laptop/komputer
        - masuk kedalam program
        - masuk kedalam text editor program
        - menulis rangkaian program yang akan dibuat
        - menentukan kondisi yang akan dijalankan
            add input * 3600 ke CAL
            CAL<=input * 3600
        - mengecek program apakah bisa dijalankan
        - apabila program berhasil dijalankan maka akan menampilkan hasil dari kondisi yang sudah di tentukan.
 
 
        1. deklarasi var input, CAL, res
        2. baca nilai dari input
        3. add input * 3600 ke CAL
            CAL<=input * 3600
        4. display CAL
 
 
    pseudocode:
        STORE "input" with any value
        STORE "res" wthout any area value
 
        CAL<=input * 3600
 
        SET "res" value with cal result
        DISPLAY "res"
 
#Project 02
    siapkan teks editor, laptop
    hidupkan laptop lalu buka teks editor kesayangan masing masing
    siapkan beberapa variabel yaitu a dan b, result
    baca variable inputan a dan b
    cocokan inputan user dengan variabel
    jika nilai a > b maka isikan pesan pada result=a terbesar
    jika nilai a<b maka isikan pesan pada result = b terbesar
    jika nilai a =b maka isikan pesan pada result="nilai a dan b sama
    tampilkan result
 
#Project 03
    siapkan teks editor, pada laptop
    hidupkan laptop lalu buka teks editor kesayangan masing masing
    deklarasikan variable jumlahTravel, hargaTiket, jenisPerjalanan
    
    STORE "jumlahTraveler" dengan value dari inputan
    STORE "hargaTiket" dengan value dari inputan
    STORE "bayar" without any area value
    STORE "jenisPerjalanan" dengan value dari inputan
 
    if "jenisPerjalanan" == twoway
        CALCULATE<="jumlahTraveler" * "hargaTiket"*2
        STORE "bayar" value with calculate result
    else 
        CALCULATE<="jumlahTraveler" * "hargaTiket"
        STORE "bayar" value with calculate result
    DISPLAY "bayar"
 
#Project 04
    STORE "n" dengan value dari inputan
    STORE "i" to 0;
 
    WHILE "i" lessthen equals "n"
    i<-i+1
    DISPLAY "i"
 
#Project 05
    STORE "n" dengan value inputan
    STORE "i" to 1
    STORE "msg" without input user
 
        FOR (i lessTehen equalsto n; i+1, msg="")
 
            IF "n"%15 equals 0
                DO "msg"= "fizzbuzz"
            ELSE IF "n"%3 equals 0
                DO "msg"="Fizz"
            ELSE IF "n"%5 equals 0
                DO "msg" = "Buzz"
            ELSE
                DO "msg" = n
