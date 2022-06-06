
## Endpoint 

- Admin Login 
- Admin Refresh  
- Admin Logout 
- Admin Dashboard 
- Admin Categories 
- Admin Add Categories 
- Admin Get Data Categories 
- Admin Update Categories Data 
- Admin Delete Data Categories 
- Admin Products 
- Admin Add Products 
- Admin Get Add Products 
- Admin Update Products 
- Admin Delete Products 
- Admin Invoices 
- Admin Customers 
- Admin Get Sliders
- Admin Add Sliders 
- Admin Delete Sliders 
- Admin Get Users

## Users 

- Admin Get Users 
- Admin Update Users 
- Admin Add Users 
- Admin Delete Users 


## Website RestFull API 

- Get Categories 
- Show Categories 
- Show Categories Products 
- Get Sliders 
- Get Provinsi 
- Get Cities 
- Check Ongkir 
- Carts 
- Add Carts 
- Total Carts 


# API Documentation 

### Admin Login 
- Method     : POST 
Request:
  - Method : GET
  - Endpoint : http://localhost:8000/api/admin/login
  - Header : 
  
          Accept: application/json
          Content-Type: application/json
          Authorization: JWT
  
  - Body   : 
  
          email: admin@gmail.com
          password: ******
  
  - Respone:

          {
              "success": true,
              "user": {
                  "id": 1,
                  "name": "Administrator",
                  "email": "admin@gmail.com",
                  "email_verified_at": null,
                  "created_at": null,
                  "updated_at": null
              },
              "token":     "token"
          }
        
   - Code : 
   
   
         200 
