# Jarkom-Modul-1-B10-2022

## Kelompok B10
| Name                      | NRP        | 
| ------------------------- | ---------- |
| Frederick Wijayadi Susilo | 5025201111 |
| Doanda Dresta Rahma       | 5025201049 |
| Zunia Aswaroh             | 5025201058 |

## 1
> Sebutkan web server yang digunakan pada "monta.if.its.ac.id"! 

Pertama, akses terlebih dahulu website http://monta.if.its.ac.id, kemudian lakukan display filter menggunakan `tcp contains "monta.if.its.ac.id"`

![image](https://user-images.githubusercontent.com/67154280/191023989-993b48fa-a66c-4680-8ebe-7b872161dd02.png)
Setelah itu, lakukan `Follow > TCP Stream`

![image](https://user-images.githubusercontent.com/67154280/191024424-7424949d-5cdb-4ae2-8044-e904b439ceb9.png)
Diperoleh webserver yang digunakan pada "monta.if.its.ac.id" dari informasi yang didapatkan yaitu `nginx/1.10.3`

## 2
> Ishaq sedang bingung mencari topik ta untuk semester ini , lalu ia datang ke website monta dan menemukan detail topik pada website “monta.if.its.ac.id” , judul TA apa yang dibuka oleh ishaq ?

## 3
> Filter sehingga wireshark hanya menampilkan paket yang menuju port 80!

## 4
> Filter sehingga wireshark hanya mengambil paket yang berasal dari port 21!

## 5
> Filter sehingga wireshark hanya mengambil paket yang berasal dari port 443!

Pertama, buka file paket yang tersedia lakukan `tcp.srcport == 443`
![image](https://drive.google.com/drive/u/0/folders/14f85-_uVA-HfheDwLzWHqmfgGv0bwvgr)

## 6
> Filter sehingga wireshark hanya menampilkan paket yang menuju ke lipi.go.id !

Pertama, buka file paket pada soal yang tersedia kemudian lakukan `tcp contains "lipi.go.id"`
![image](https://drive.google.com/drive/u/0/folders/14f85-_uVA-HfheDwLzWHqmfgGv0bwvgr)
 
 kemudian ping pada cmd pada "lipi.go.id"
 ![image](https://drive.google.com/drive/u/0/folders/14f85-_uVA-HfheDwLzWHqmfgGv0bwvgr)

## 7
> Filter sehingga wireshark hanya mengambil paket yang berasal dari ip kalian!

pertama, cek ip sendiri di cmd . lakukan `ipconfig`
![image](https://drive.google.com/drive/u/0/folders/14f85-_uVA-HfheDwLzWHqmfgGv0bwvgr)

kemudian lakukan source ip sendiri di display filter. lakukan `ip.src == 10.8.108.239`
![image](https://drive.google.com/drive/u/0/folders/14f85-_uVA-HfheDwLzWHqmfgGv0bwvgr)

## 8
> 

## 9
> 

## 10
> 
