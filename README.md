# Persepsi Publik Terhadap Christopher Nolan: Analisis Review Film Menggunakan model IBM Granite
# Raw dataset link
Dataset: imdb dataset of 50k movie reviews <br/>
Link: https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews <br/>
Sumber: kaggle <br/>
Deskripsi: Dataset publik ini berisi 50.000 ulasan film dari situs IMDb, lengkap dengan label sentimen 'positif' atau 'negatif'.
# Project Overview
Christopher Nolan adalah salah satu sutradara paling berpengaruh di era modern, dikenal dengan gaya penceritaan yang kompleks dan visual yang megah. Namun, karyanya seringkali memecah belah opini publik, menciptakan sebuah pertanyaan yang relevan: elemen-elemen spesifik apa dalam gaya penyutradaraannya yang menjadi inti dari pujian sekaligus kritik dari para penonton? <br/>
Proyek ini bertujuan untuk menjawab pertanyaan tersebut dengan menganalisis sentimen dan tema dari ulasan film yang tersedia secara publik. Dengan memanfaatkan dataset IMDb yang berisi puluhan ribu ulasan, proyek ini menggunakan pendekatan yang dibantu oleh AI untuk menggali wawasan yang bermakna. <br/><br/>
Pendekatan analisis dilakukan secara sistematis:<br/>
<b>Pertama</b>, menyaring ulasan yang secara spesifik membahas karya Nolan. lalu, memisahkan ulasan tersebut berdasarkan sentimen positif dan negatif.<br/>
<b>Kedua</b>, sebuah Large Language Model (LLM) digunakan untuk melakukan analisis dan peringkasan tematik pada kedua kelompok data tersebut. Tujuannya adalah untuk mengekstrak dan menyajikan tema-tema utama yang secara konsisten dipuji dan dikritik, sehingga memberikan pemahaman yang lebih dalam mengenai persepsi publik terhadap gaya khas Christopher Nolan.
# Insight & Findings
- Hal yang Paling Dipuji Penonton (Berdasarkan hasil analisis review positif) <br/>
1. Penceritaan Unik & Non-Linear <br/>
Penonton menyukai alur cerita yang kompleks dan tidak lurus yang menantang mereka untuk berpikir (contoh: Memento, Inception). <br/>
2. Karakter Kuat & Penampilan Ikonik <br/>
Karakter-karakternya dianggap mendalam dan berkesan, didukung oleh penampilan kuat para aktornya (contoh: Joker oleh Heath Ledger). <br/>
3. Gaya Visual & Atmosfer yang Khas <br/>
Film-filmnya dikenal memiliki sinematografi yang megah dan atmosfer yang imersif, seringkali menggunakan efek praktis. <br/>

- Hal yang Paling Dikritik Penonton (Berdasarkan hasil analisis review negatif) <br/>
1. Alur Cerita Terlalu Rumit <br/>
Bagi sebagian penonton, plot yang kompleks dianggap membingungkan dan sulit untuk diikuti. <br/>
2. Audio Mixing (Dialog Tidak Jelas) <br/>
Kritik yang sering muncul adalah dialog karakter yang tenggelam oleh musik atau suara latar yang terlalu keras. <br/>
3. Karakter Terasa "Dingin" <br/>
Beberapa penonton merasa karakter-karakternya kurang memiliki kedalaman emosional dan lebih fokus pada konsep atau ide.<br/>
# AI Support Explanation
1. Peran AI dalam Proyek <br/>
Dalam proyek ini, AI (Model IBM Granite) tidak hanya digunakan untuk tugas klasifikasi sederhana, melainkan untuk kapabilitas yang lebih canggih, yaitu peringkasan tematik (thematic summarization). <br/>
2. Nilai Tambah dari AI <br/>
Pemanfaatan ini memungkinkan proyek untuk melampaui sekadar sentimen 'suka/tidak suka' dan menggali wawasan yang lebih dalam mengenai "mengapa" penonton memiliki persepsi tertentu, sehingga menghasilkan insight yang lebih kaya dan bermakna. <br/>
3. Proses Pemanfaatan AI <br/>
Model AI diberi input berupa kumpulan besar teks ulasan (baik positif maupun negatif) dan diinstruksikan untuk menganalisis serta menyarikan alasan-alasan utama yang berulang di dalam teks tersebut. <br/>
