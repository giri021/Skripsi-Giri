# Skripsi-Giri

PAPAN LATIH BULUTANGKIS BERBASIS
 MIKROKONTROLER AT89S51

AGUSTINUS GIRI HARTONO 

Pada umumnya pemain bulutangkis berlatih dengan metode circuit
training secara manual dalam durasi yang sudah ditentukan. Secara manual,
dengan mengikuti instruksi pelatih. Pelatih menunjukan arah kemana pemain
harus bergerak. Terdapat 6 titik yang sudah ditentukan di lapangan bulutangkis.
Dengan cara yang sama, pelatih menggunakan sebuah alat untuk berlatih. Pelatih
menekan satu dari 6 tombol operator untuk menghidupkan salah satu lampu.
Pemain harus mengikuti kemana arahan dari lampu yang menunjukkan kepada
pemain titik mana yang harus dituju.
Circuit Trainer menggunakan Mikrokontroler AT89S51 sebagai
pengendali. Circuit Trainer terdiri dari 8 tombol trainer, 8 Lampu AC 5 watt,
Speaker, 2 digit seven segment untuk Penampil Durasi dan Kecepatan, 2 digit
seven segment untuk menampilkan skor benar dan skor salah. Alat ini bekerja
dengan 9 kombinasi mode. Pemain dapat mengkombinasikan Mode durasi
antara 30 detik, 60 detik, atau 90 detik dengan Mode Kecepatan yang terdiri dari
3S,4S,dan 5S. Mekanisme penyalaan lampu AC trainer tergantung oleh data
pada tabel tengok. Alamat low byte tabel tengok diacak dengan menggunakan
metode LFSR (Linear Feedback Shift Register) 8 bit membentuk sebuah data
yang seolah-olah teracak. Trainer ini bekerja dengan diawali bunyi speaker
selama 2 detik dan diakhiri dengan bunyi speaker selama 5 detik. Hasil circuit
trainer akan ditampilkan pada ruas penampil.
 Hasil pengamatan menunjukkan alat ini mampu bekerja sebagai
pengganti peran pelatih sebagai instruktur sekaligus operator. Proses pengacakan
posisi nyala lampu dapat bekerja dengan baik namun tidak terdistribusi secara
seragam. Error selisih waktu yang terjadi pada mode durasi dapat ditoleransi
karena kurang dari 3.0 detik. Error untuk mode kecepatan dapat ditoleransi
sebab nilainya hanya 0.1 detik, selisih waktu ini tidak dapat dirasakan oleh
pemain.
Kata kunci : Circuit Training, MCS-51, Aplikasi Mikrokontroler AT89S51, Pembangkit Angka Acak

BADMINTON CIRCUIT TRAINER BASED ON
 AT89S51 MICROCONTROLLER

 AGUSTINUS GIRI HARTONO 

ABSTRACT
Generally, a badminton player practices by using a circuit training
method manually with a setted duration. And manually, the player follows the
coach instruction. The coach gives the direction where the player should move.
There are six nodes that are set on the badminton pitch. In the same method, the
coach uses a tool to do the training. The coach presses one of the six buttons on
the operator’s buttons to make one of six lamps on. The player should follows
the direction of the lamp, that directs the player to the desired node.If the lamp
one is on, the player must move to node one and so on.
Circuit Trainer uses AT89S51 microcontroller to drive the system of the
trainer. There are 8 trainer buttons, 8 lamps, 1 speaker, 2 digit seven segment
used to display the duration trainer and missed score, 2 digit seven segment used
to show the trainer speed and the right score. There are 9 combination modes.
The player can combine the duration mode between 30 seconds, 60 seconds or
90 seconds with the speed mode 3S, 4S, and 5S. The mechanism that makes one
of 8 lamps on depends on the data in the look-up table. The low address of the
look-up table will be randomized by using 8 bits LFSR (Linear Feedback Shift
Register) method to generate random number. The circuit trainer will be started
by the sound of the speaker for 2 seconds, and will be ended with the sound of
the speaker for 5 seconds. The result of circuit trainer will be displayed on
seven segments.
The result of this study show that, the circuit trainer can do what the
coach instructs or the operator does. The random method to make one of the 8
lamps on works but the distribution of the lamp which is on is not the same. The
error on the duration mode can be tolerated because the value is less than 3.0
seconds. The error on the speed mode can be tolerated because the value is 0.1
second and the player can not feel it.
Keywords: Circuit Training, Pseudo random, MCS-51, AT89S51
 Microcontroller application
