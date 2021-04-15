## Welcome 

## table of contents
- [Setup Developers Tools Dowload File pre-requisite](#Pre-Requisite)
  - Install and Download   
- [GIT](#git)
  - Basic GIT
  - Create  Github Account      
- [Programming Language](#Programming Languages)
  - Pengertian Programming Language
  - why .net / or c# 
- [Apa itu API / Application Program Interface](#api)
  - Penngertian API
  - Pengertian CRUD
  - Membuat API dan CRUD Sederhana Dengan C# Asp.Net.Core Framework 
- [Database / basis data](#database)
  - Basic SQL Server
  - Basic database
  - CRUD
- Deployment
  - Pengertian publish
  - Docker / Conteiner
  - Register Cloud
    - [Azure](https://azure.microsoft.com/en-us/features/azure-portal/)
    - [AWS](https://aws.amazon.com/free/?trk=ps_a134p000003yHpDAAU&trkCampaign=acq_paid_search_brand&sc_channel=PS&sc_campaign=acquisition_ID&sc_publisher=Google&sc_category=Core&sc_country=ID&sc_geo=APAC&sc_outcome=acq&sc_detail=aws%20free%20tier&sc_content=Account_e&sc_segment=444351556713&sc_medium=ACQ-P|PS-GO|Brand|Desktop|SU|AWS|Core|ID|EN|Text&s_kwcid=AL!4422!3!444351556713!e!!g!!aws%20free%20tier&ef_id=Cj0KCQjwpdqDBhCSARIsAEUJ0hMtisTsB7Pl4b0yZvn6UmcuYQq3ihrd0oGEJ8C8dDag90Tk1HPxCXkaAlETEALw_wcB:G:s&s_kwcid=AL!4422!3!444351556713!e!!g!!aws%20free%20tier&all-free-tier.sort-by=item.additionalFields.SortRank&all-free-tier.sort-order=asc&awsf.Free%20Tier%20Types=*all&awsf.Free%20Tier%20Categories=*all)
    - [Alibaba](https://account.alibabacloud.com/register/intl_register.htm?spm=a3c0i.259011.6791778070.53.7c224adfamca4V&oauth_callback=https%3A%2F%2Fid.alibabacloud.com%2F&)
    - [GCP](https://console.cloud.google.com/freetrial?_ga=2.39226599.594441864.1618457512-406532934.1612620373&_gac=1.194518239.1618457512.Cj0KCQjwpdqDBhCSARIsAEUJ0hOrckAMxrzvxETgqAU-BZaE9hiIFP6asZCjtpj6myK2GAvSyzgWpbUaAqL0EALw_wcB)
    - [ORACLE](https://www.oracle.com/cloud/free/)
    - [OVH](https://www.ovh.com/asia/lp/public-cloud-trial/?xtor=SEC-13-GOO-[GG-LAB-ID-EN-SRC-OFF-GENERIC(Cloud-Services)]-[437013752568]-S-[%2Bcloud%20%2Bfree]&xts=563736&sitelink=&gclid=Cj0KCQjwpdqDBhCSARIsAEUJ0hOgCzzG8WHkEhMHRUXbFDCKuVjGvSFNk2m4e048VCsaiHVeOgTk4fEaAnRNEALw_wcB)
    - [Vultr](https://www.vultr.com/)
    - [DigitalOcean](https://www.digitalocean.com/)
    - [Heroku](https://www.heroku.com/)
    - [Netlify](https://www.netlify.com/)
    - [Vercel](https://vercel.com/)

- Visual Studio and Visual Studio Code
- Cheatseat
- [MarkDown](#markdownn)


### Pre-Requisite
Setup Developers Tools Dowload File **pre-requisite**.

Istallation  Tools, Please downnload and install the link below:

- [Install Git](https://git-scm.com/download/win)
- [Visual Studio 2019 Community](https://visualstudio.microsoft.com/downloads/)
- [Visual-Studio-Code](https://code.visualstudio.com/)
- [SQL Server 2019 Developer-Edition](https://go.microsoft.com/fwlink/?linkid=866662)
- [Docker Desktop](https://www.docker.com/products/docker-desktop)

### GIT
[GIT merupakan sebuah komponen penting dalam dunia developers](https://idcloudhost.com/mengenal-apa-itu-git-serta-manfaat-dan-fiturnya-untuk-developer/)  
Fungsi utama git yaitu [mengatur versi dari source code program anda](https://idcloudhost.com/pengertian-dan-manfaat-git-bagi-developer/) dengan mengasih tanda baris dan code mana yang ditambah atau diganti.
[yuk pahami git lebih lanjut](https://www.youtube.com/watch?v=lTMZxWMjXQU&list=PLFIM0718LjIVknj6sgsSceMqlq242-jNf)

```git
Command Line   
Git init : untuk membuat repository pada file lokal yang nantinya ada folder .git
Git status : untuk mengetahui status dari repository lokal
Git add : menambahkan file baru pada repository yang dipilih
Git commit : untuk menyimpan perubahan yang dilakukan, tetapi tidak ada perubahan pada remote repository.
Git push : untuk mengirimkan perubahan file setelah di commit ke remote repository.
Git branch : melihat seluruh branch yang ada pada repository
Git checkout : menukar branch yang aktif dengan branchyang dipilih
GIt merge : untuk menggabungkan branch yang aktif dan branch yang dipilih
Git clone : membuat Salinan repository lokal

```


[Membuat Account Github](https://github.com/join)

Apa itu Gthub?
sederhana-nya github ada host atau tempat kita menyimpan source code / file kita. 

[github student](https://education.github.com/pack)


### PROGRAMMING LANGUAGE
Untuk membuat komputer melakukan sesuatu, kita harus memberi mereka makan dengan instruksi yang tepat. Serangkaian instruksi ini disebut "program". 

Mari kita ambil contoh. Bayangkan sebuah program yang meminta pengguna untuk mengetikkan dua angka. Program menambahkan angka-angka tersebut, dan hasilnya kemudian ditampilkan di monitor. Instruksi yang harus ditulis adalah:

Output "Silakan ketik nomor pertama Anda dan tekan enter" pada monitor.
Saat nomor diketik dan tombol "Enter" ditekan pada keyboard, simpan nomor tersebut ke dalam memori. Mari kita nyatakan AA sebagai angka ini.
Output "Silakan ketik nomor kedua Anda dan tekan enter" pada monitor.
Saat nomor diketik dan tombol "Enter" ditekan pada keyboard, simpan nomor tersebut ke dalam memori. Mari kita nyatakan BB nomor ini.
Kirim ke ALU dua angka (AA dan BB) dan opcode tambahan dan simpan hasilnya ke dalam memori.
Keluarkan hasilnya di monitor
Dua jenis instruksi dilakukan:
Operasi I / O: mengambil nomor yang disimpan ke dalam memori, menyimpan nomor ke dalam memori dari perangkat input (keyboard), memuat data dari memori, dan menampilkannya kepada pengguna.
Operasi aritmatika: tambahkan dua angka.

Di sini kami memiliki seperangkat instruksi yang ditulis dalam bahasa Inggris biasa. 
Mesin tidak memahami kalimat bahasa Inggris. Kalimat tersebut perlu diterjemahkan ke dalam bahasa yang dimengerti mesin. Bahasa apakah ini?

Bagaimana cara berbicara dengan mesin?

Bahasa pemrograman adalah bahasa formal
Instruksi yang diberikan ke mesin ditulis dengan bahasa pemrograman. Bahasa pemrograman adalah bahasa formal yang terdiri dari kata-kata yang dibangun dari alfabet (sekumpulan karakter berbeda). Kata-kata itu diatur mengikuti aturan khusus. Go adalah bahasa pemrograman, seperti x86 Assembly, Java, C, C ++, Javascript ...

Mereka adalah dua jenis bahasa pemrograman:
Level rendah
Level tinggi

Bahasa pemrograman tingkat rendah lebih mirip dengan instruksi unit pemrosesan. Bahasa tingkat yang lebih tinggi menyediakan konstruksi yang membuatnya lebih mudah dipelajari dan digunakan sehari-hari.

Beberapa bahasa tingkat tinggi dikompilasi, yang lain diinterpretasikan, dan beberapa di antaranya. Kita akan melihat di bagian selanjutnya apa arti kedua istilah tersebut.

[source](https://www.practical-go-lessons.com/chap-1-programming-a-computer)

### API
[API](https://www.niagahoster.co.id/blog/api-adalah/) atau Application Programming Interface adalah sebuah **interface** yang dapat menghubungkan aplikasi satu dengan aplikasi lainnya. Jadi, API berperan sebagai **perantara antar berbagai aplikasi berbeda**, baik dalam satu platform yang sama atau lintas platform.

### DATABASE
[Database](https://www.gurupendidikan.co.id/pengertian-database/) ( basis data ) atau dengan sebutan pangkalan data ialah suatu kumpulan sebuah informasi yang disimpan didalam sebuah perangkat komputer secara sistematik sehingga dapat diperiksa dengan menggunakan suatu program komputer agar dapat informasi dari basis data tersebut.

```sql

`#Create`
Insert Into Article(id,Title,Content,Description)
Values (1,'How To be a developers', 'fast way to be a developers','follow this step')

`#Read`
select * from Article

select * from Article where id = 1

`#Update`
Update Article Set Content = 'fast way to be a developers in nowaday's'

`#Delete`
Delete Article where id = 1

```


### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
