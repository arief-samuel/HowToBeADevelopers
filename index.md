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
    - Azure
    - AWS
    - Alibaba
    - GCP
    - ORACLE
    - OVH
    - Vultr
    - DigitalOcean
    - Heroku
    - Netlify
    - Vercel 

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
To make computers do something, we have to feed them with precise instructions. This set of instructions is called “program”.

Let’s take an example. Imagine a program that asks the user to type two numbers. The program adds those numbers, and the result is then displayed on the monitor. The instructions that have to be written are :

Output “Please type your first number and press enter” on the monitor.
When a number is typed and the “Enter” key is pressed on the keyboard, store the number into memory. Let’s denote AA this number.
Output “Please type your second number and press enter” on the monitor.
When a number is typed and the “Enter” key is pressed on the keyboard, store the number into memory. Let’s denote BB this number.
Send to the ALU the two numbers (AA and BB) and the addition opcode and store the result into memory.
Output the result on the monitor
Two types of instructions are performed :
I/O operations : retrieve numbers stored into memory, store numbers into memory from an the input device (the keyboard), load data from memory, and display it to the user.
An arithmetic operation : add two numbers.
We have here a set of instructions that are written in plain English. The machine does not understand English sentences. Those sentences need to be translated to a language that the machine understands. What is this language?

×The paper and the digital edition of this book are available! More info here.
How to speak to the machine? 

Programming languages are formal languages 
Instructions that are given to the machine are written with programming languages. Programming languages are formal languages.They are composed of words that are constructed from an alphabet (a set of distinct characters). Those words are organized following specific rules. Go is a programming language, like x86 Assembly, Java, C, C++, Javascript...

They are two types of programming languages :
Low level
High level

Low-level programming languages are closer to the processing unit’s instructions. Higher-level languages provide constructs that make them easier to learn and to use on a day-to-day basis.

Some high-level languages are compiled, others are interpreted, and some are in between. We will see in the next sections what those two terms mean.


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
