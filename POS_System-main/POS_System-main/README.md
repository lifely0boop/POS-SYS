# 🍽️ Restaurant POS System | QT Platform  

**A secure, role-based Point of Sale system for restaurants, with manager/employee logins and order management.**  

## 🔍 Project Health  
[![OpenSSF Scorecard](https://api.securityscorecards.dev/projects/github.com/djon-tell/POS_System/badge)](https://securityscorecards.dev/viewer/?uri=github.com/djon-tell/POS_System)  
[![OpenSSF Best Practices](https://www.bestpractices.dev/projects/10347/badge)](https://www.bestpractices.dev/projects/10347) 
## 📋 Features  
- **Role-Based Access**:  
  - 👨‍💼 **Manager**: Add/remove employees, view sales reports.  
  - 👩‍🍳 **Employee**: Take orders, process payments.  
- **Order Management**: Create, modify, and track orders in real-time.  
- **QT GUI**: Cross-platform desktop interface.  

## 👥 Team Members  
- [Djon Leon](https://github.com/djon-tell)  
- [Noah musselwhite](https://github.com/nmusselwhite)  
- [Ahmed ben ammar]  

---

## ⚙️ Installation (For Developers)  
### Prerequisites  
- QT 6.x  
- C++17 compiler  

# 1. Clone your repository
git clone https://github.com/djon-tell/POS_System.git
cd POS_System

# 2. Build with qmake (your .pro file is named "POS.pro")
mkdir build && cd build
qmake ../POS.pro  # Points to your actual .pro file
make

# 3. Run the executable (named "POS" per your .pro TARGET)
./POS

