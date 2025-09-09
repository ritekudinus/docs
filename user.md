## 🔑 Authentication

### POST `/api/auth/register`
**Deskripsi:** Registrasi user baru  
**Body Request:**
```json
{
  "nama": "John Doe",
  "username": "johndoe",
  "email": "john@example.com",
  "password": "password123",
  "role": "admin"
}
```
**Response:**
```json
{
  "status": true,
  "message": "User registered successfully",
  "data": {
    "id_user": 1,
    "nama": "John Doe",
    "username": "johndoe",
    "email": "john@example.com",
    "role": "admin"
  }
}
```
