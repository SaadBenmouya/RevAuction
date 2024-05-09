# RevAuction

# My App

## Project Structure
'''
my-app/
├── backend/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/
│   │   │   │   └── com/example/
│   │   │   │       ├── config/
│   │   │   │       │   └── SecurityConfig.java   
│   │   │   │       ├── controller/
│   │   │   │       │   ├── AuthController.java   (Saad)
│   │   │   │       │   ├── CustomerController.java (Saad)
│   │   │   │       │   ├── SupplierController.java (Aymane)
│   │   │   │       │   ├── AdminController.java (Aymane)
│   │   │   │       │   └── BidController.java (Elmahdi)
│   │   │   │       ├── model/
│   │   │   │       │   ├── User.java (Saad)
│   │   │   │       │   ├── Customer.java (Saad)
│   │   │   │       │   ├── Supplier.java (Aymane)
│   │   │   │       │   ├── Admin.java (Aymane)
│   │   │   │       │   ├── Bid.java (Elmahdi)
│   │   │   │       │   └── BidOffer.java (Elmahdi)
│   │   │   │       ├── repository/
│   │   │   │       │   ├── UserRepository.java (Saad)
│   │   │   │       │   ├── CustomerRepository.java (Saad)
│   │   │   │       │   ├── SupplierRepository.java (Aymane)
│   │   │   │       │   ├── AdminRepository.java (Aymane)
│   │   │   │       │   ├── BidRepository.java (Elmahdi)
│   │   │   │       │   └── BidOfferRepository.java (Elmahdi)
│   │   │   │       ├── security/
│   │   │   │       │   ├── jwt/
│   │   │   │       │   │   └── JwtUtils.java
│   │   │   │       │   └── services/
│   │   │   │       │       ├── UserDetailsImpl.java (Saad)
│   │   │   │       │       └── UserDetailsServiceImpl.java (Saad)
│   │   │   │       └── MyAppApplication.java (Done)
│   │   │   └── resources/
│   │   │       └── application.properties   
│   │   └── pom.xml
│   └── ...
├── frontend/
│   ├── node_modules/
│   ├── public/
│   │   ├── index.html
│   │   └── ...
│   ├── src/
│   │   ├── components/
│   │   │   ├── auth/
│   │   │   │   └── Login.js
│   │   │   ├── customer/
│   │   │   │   ├── CustomerDashboard.js
│   │   │   │   └── BidOfferForm.js
│   │   │   ├── supplier/
│   │   │   │   ├── SupplierDashboard.js
│   │   │   │   └── BidResponseForm.js
│   │   │   ├── admin/
│   │   │   │   └── AdminDashboard.js
│   │   │   └── ...
│   │   ├── services/
│   │   │   ├── auth.service.js
│   │   │   └── bid.service.js
│   │   ├── App.js
│   │   ├── index.js
│   │   └── ...
│   ├── package.json
│   └── ...
└── ...
'''
