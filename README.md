# Automatic-Coffee-Mixer-Simulator
Abstrak - Kopi adalah minuman yang banyak orang konsumsi sebagai hidangan penyemangat dan hidangan pada saat waktu bersantai. Aktivitas mengkonsumsi kopi bisa menghilangkan pikiran jenuh akibat kesibukan sehari-hari. Oleh karena itu, kopi sangat bermanfaat bagi masyarakat khususnya para penikmat kopi. Namun dalam penyajian takaran membuat minuman kopi di warung atau cafe masih menggunakan cara manual, sehingga takaran kopi tidak tepat. Apabila membuat minuman kopi dengan jumlah yang banyak mungkin ada beberapa minuman kopi memiliki rasa yang berbeda. Oleh karena itu dibuat alat pencampur kopi otomatis agar takaran minuman kopi yang dihasilkan memiliki rasa yang sama. Perancangan sistem pada alat pembuat minuman kopi otomatis dibantu menggunakan program aplikasi LabVIEW, dengan metode pengontrol PID untuk mengatur kadar kandungan dalam kopi yang ingin disajikan. Parameter kadar kandungan yang akan diatur adalah kopi, susu, dan gula dengan mengatur nilai Kp=398,52; nilai Ki=3,06; dan nilai Kd=0,765. Dengan mengatur set point maka nilai kadar yang sudah tercampur akan tetap stabil sesuai dengan keinginan.  Kata kunci : PID, Tunning PID, Simulasi Pencampur Kopi, LabVIEW, Coffe Mixer Simulation, PID simulation  Abstract - Coffee is a drink that many people consume as an encouraging and casual meal. Coffee consumption can eliminate boredom due to daily activities. Therefore, coffee is very beneficial for people who enjoy coffee. But in serving doses of making coffee drinks in stalls or cafes still use manual methods, so the dose of coffee is not right. Every time you make a large amount of coffee drinks there may be several coffee drinks with different flavors. Therefore an automatic coffee maker is made so that the resulting coffee drink has the same taste. The system design for automatic coffee drink makers uses the LabVIEW application program, with the PID controller method to get the coffee content that you want to serve. The parameters of the content to be regulated are coffee, milk and sugar by setting the value of Kp = 398.52; Ki= 3.06; and Kd= 0.765. By setting a point, the value of the mixed content will remain stable as desired.  Keyword ¬: PID, Tunning PID, Coffe Mixer Simulation, LabVIEW, PID simulation, Coffe Mixer PID

	==Cara Pengoperasian Simulasi==
Untuk melakukan pengoperasian simulasi mesin pencampur kopi ini sebagai berikut.
•	Pertama, file simulasi dapat di download pada alamat berikut:
https://github.com/adyezh/Automatic-Coffe-Mixer-Simulator
•	Tedapat 2 file yaitu PID dan UTS PID
•	Buka file yang bernama UTS PID 
•	Kemudian isi semua nilai Kp, Ki, dan Kd sesuai dengan hasil dari Tunning PID
•	Tentukan nilai Set Point Kopi, Gula, dan Susu hingga jumlah dari ketiganya mencapai 100. Misalkan nilai set point kopi 50, dan set point gula 25, lalu nilai set point susu harus 25.
•	Jalankan program dan tunggu hingga tangki terisi penuh.
•	Kemudian buka katup control output sebesar 50 untuk memberikan gangguan.
•	Dan pada tahap terakhir tunggu hingga nilai %kadar kopi, gula, dan susu stabil. Maka itulah hasil dari kadar output yang didapatkan 
Untuk cara pengoperasian yang lebih jelas dapat diakses videonya melalui alamat berikut ini.
https://www.youtube.com/watch?v=HpZFFrGTOT0&t=2s


== How to Operation Simulation ==
To carry out the operation of this coffee mixing machine simulation as follows.
• First, the simulation file can be downloaded at the following address:
https://github.com/adyezh/Automatic-Coff-Mixer-Simulator
• There are 2 files, PID and PID UTS
• Open the file called UTS PID
• Then fill in all values of Kp, Ki, and Kd according to the results of Tunning PID
• Determine the value of the Coffee Set, Sugar, and Milk until the number of all three reaches 100. Suppose the coffee set point value is 50, and the sugar set point is 25, then the milk set point value must be 25.
• Run the program and wait until the tank is fully loaded.
• Then open the output control valve by 50 to provide interference.
• And in the last stage wait until the value of% coffee, sugar and milk is stable. So that's the result of the level of output obtained
For clearer operations, the video can be accessed through the following address.
https://www.youtube.com/watch?v=7khUcmzjd2I
