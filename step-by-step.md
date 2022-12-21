install package.json
- npm init -y

Install Depedensi (express, express-session, body-parser, req-flash, mysql, ejs)
- npm i express express-session body-parser req-flash mysql ejs

1. express sebagai kerangka kerja Node.js
2. express-session yang dibutuhkan untuk sesi user ketika login
3. body-parser untuk menghandle input yang dilakukan user
4. req-flash yang digunakan untuk memberi notifikasi error ataupun sukses
5. mysql sebagai koneksi sistem ke database
6. ejs sebagai template engine untuk disajikan ke browser user

Database
- nama database : db_node_login
- nama table : table_user
- field : user_id, user_name, user_email, user_password

Running project
- node  index.js
- http://localhost:5050/