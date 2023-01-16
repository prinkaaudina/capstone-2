# capstone-2

# Latar Belakang
Seorang *youtuber* mempekerjakan seorang *data analyst* untuk memberikan *insight* agar video-video yang dibuat oleh channelnya menjadi trending.

## Pernyataan Masalah
*Youtuber* tersebut ingin mengetahui **apa saja faktor yang mempengaruhi sebuah video menjadi trending di US**. Informasi ini akan membantu *youtuber*  tersebut untuk menyesuaikan tipe konten yang akan dibuatnya sehingga biaya produksi menjadi efektif dan tepat sasaran.

Sebagai seorang *data analyst*, saya akan mencoba menjawab pertanyaan berikut:

**Bagaimana karakteristik video yang harus dibuat agar video tersebut menjadi trending di Youtube US?**
1. Apa faktor utama yang membuat sebuah video menjadi trending?
2. Apakah jam tayang video mempengaruhi performa video untuk menjadi trending?
3. Berapa lama waktu yang dibutuhkan agar sebuah video menjadi video yang trending?
4. Kategori apa yang paling diminati penonton pada video yang trending?

# Data
Dataset yang digunakan untuk menganalisa video Youtube yang trending di US dapat diakses [di sini](https://www.kaggle.com/datasets/datasnaek/youtube-new). Dataset tersebut merupakan dataset yang berisi data selama beberapa bulan tentang video Youtube yang sedang *trend* setiap harinya di wilayah US.

Dataset ini berisi informasi terkait karakteristik dari setiap video yang trending di US. Terdapat 16 kolom pada dataset USvideos, yaitu:  

* video_id: ID dari setiap video
* trending_date: Tanggal video tersebut trending
* title: Judul video
* channel_title: Nama channel dari video tersebut
* category_id: Kategori dari video tersebut
* publish_time: Waktu video ditayangkan
* tags: Tags yang digunakan pemilik channel
* views: Jumlah penonton pada video tersebut
* likes: Jumlah like pada video tersebut
* dislikes: Jumlah dislike pada video tersebut
* comment_count: Jumlah komentar pada video tersebut
* thumbnail_link: Link ke thumbnail video
* comments_disabled: Apakah komentar diaktifkan atau tidak
* ratings_disabled: Apakah video tersebut termasuk ke dalam rating atau tidak
* video_error_or_removed: Apakah video tersebut pernah dihapus atau tidak
* description: Deskripsi dari video tersebut
