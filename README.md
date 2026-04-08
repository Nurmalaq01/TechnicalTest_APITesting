                  Technical test Answer - QA Automation Intern
                                Ade Nisa Nurmala Sari
Project test untuk API testing dengan menggunakan public API : https://jsonplaceholder.typicode.com 
Dimana tools yang dipakai adalah Spreadsheet untuk membuat test scenario nya dan Postman untuk melakukan automation testnya

Cara untuk run test nya :
- Download file yang ada pada repository ini
- Buka aplikasi postman
- Import file ke dalam Postman
- Buka setiap request dan klik button "Send" untuk melihat hasil dari masing-masing request

Ada beberapa test di dalam project Postman ini
1. Response type id is passed -> adalah respons test yang harus dikeluarkan disaat request mengirim tipe data "id" sebagai number
2. Response type id is failed -> adalah respons test yang harus dikeluarkan disaat request mengirim tipe data yang salah
3. Get all data -> untuk display semua data yang bisa diakses pada penyimpanan database
4. Return request 200 ->adalah respons test yang harus dikeluarkan disaat program dapat menjalankan Get/ambil data dengan benar
5. Return data with id 18 -> adalah display data yang memiliki id dengan nomor "18"
6. Return data with userId 5 -> adalah display data yang memili userId dengan nomor "5"
7. Input new data -> adalah menambahkan data baru pada database
8. Return request 201 -> adalah respons test yang harus dikeluarkan disaat program dapat menjalankan Post/create data dengan benar
9. Input with empty data -> adalah respons yang dikeluarkan disaat salah satu field tidak diisi saat input data
