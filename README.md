"# simple_auth" 
# SIMPLE AUTH

## 🧩 Description
Bài lab thực hành xác thực cơ bản trong NodeJS bằng **Basic Auth** và **Cookie Auth**.

---

## ⚙️ Run project
```bash
npm install
node basic_auth.js
# hoặc
node cookie_auth.js
```

---

## 🧪 Test with Postman

### 🔹 Test Basic Auth
**Endpoint:** `GET http://localhost:3000/profile`

**Authorization type:** Basic Auth  
- Username: `admin`  
- Password: `123456`

📸 *Kết quả test:*  
![Basic Auth Result](public/results/basic_auth.png)

---

### 🔹 Test Cookie Auth
**Endpoint:**  
1. `POST http://localhost:3000/login`  
2. Kiểm tra cookie trong Postman → Cookies  
3. `GET http://localhost:3000/profile`

📸 *Kết quả test:*  
![Cookie Auth Result](public/results/cookie_auth.png)

---

## 📘 Author
**22670361 - Võ Thị Cẩm Tú**
