## 📘 My Personal Notes

### 🗓️ Week 9: Database Design using Entity Relationship Diagram

#### 📍 Definition and Purpose of Database
- _Poin-poin Utama_ :
  1. Database Design using Entity Relationship Diagram
     Database Design using Entity Relationship Diagram merujuk pada proses merancang struktur dan hubungan antar entitas atau objek dalam sebuah database menggunakan model Entity Relationship Diagram (ERD)
  2. Tujuan
     Mempertahankan integritas data dengan mengatur keterkaitan dan batasan antar entitas dalam database..
- _Contoh/Use-Case_
  1. ## Entity
       - Developer
       - Customer
       - Project

     ## Relation
       - Assign

- _Catatan Tambahan_
 - 

#### 📍 View of Data
- _Poin-poin Utama_
  1. Hubungan antar 3 entitas 
- _Contoh/Use-Case_
  Dalam sebuah relasi ternary, batasan kardinalitas (cardinality) dapat dinyatakan dengan notasi 
seperti berikut:
- (1, 1, n): Contohnya, satu Customer memberikan satu Project kepada satu Developer, namun 
satu Project bisa dikerjakan oleh banyak Developer.
- (1, n, 1): Contohnya, satu Customer memberikan banyak Project, namun setiap Project hanya 
  dikerjakan oleh satu Develope
- _Catatan Tambahan_
  1. 

#### 📍Unary Relationship, Binary Relationship, and Ternary Relationship
- _Poin-poin Utama_
  1. Unary Relationship, Binary Relationship, and Ternary Relationship
- _Contoh/Use-Case_
  1. Unary Relationship: Relasi antara satu entitas dengan dirinya sendiri. Contoh: "employee supervises employee".
  2. Binary Relationship: Relasi antara dua entitas. Contoh: "customer buys product".
  3. Ternary Relationship: Relasi antara tiga entitas. Contoh: "student enrolls in course offered by department".
- _Catatan Tambahan_
  


### 📍 Reference
1. [uph-site]([https://www.oracle.com/in/database/what-is-database/](https://uph365-my.sharepoint.com/personal/feliks_parningotan_uph_edu/_layouts/15/stream.aspx?id=%2Fpersonal%2Ffeliks%5Fparningotan%5Fuph%5Fedu%2FDocuments%2FU%20%20%2D%20%20P%20%20%2D%20%20H%2F2%2E%20Reguler%2F2023%2D1%2FSistem%20Basis%20Data%2Fch9%20%2D%20ER%5Fdiagram%5F1%2Emov&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0RpcmVjdCJ9fQ&ga=1&referrer=StreamWebApp%2EWeb&referrerScenario=AddressBarCopied%2Eview)https://uph365-my.sharepoint.com/personal/feliks_parningotan_uph_edu/_layouts/15/stream.aspx?id=%2Fpersonal%2Ffeliks%5Fparningotan%5Fuph%5Fedu%2FDocuments%2FU%20%20%2D%20%20P%20%20%2D%20%20H%2F2%2E%20Reguler%2F2023%2D1%2FSistem%20Basis%20Data%2Fch9%20%2D%20ER%5Fdiagram%5F1%2Emov&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0RpcmVjdCJ9fQ&ga=1&referrer=StreamWebApp%2EWeb&referrerScenario=AddressBarCopied%2Eview)

