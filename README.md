# E-Commerce Platform for Computer Hardware and Gaming Gears

**สมาชิก**
- 67144643 สุรวุฒิ บุญยู้ ( Leader Dev & Project Manager )
- 67150490 เชษฐกิตติ์ สืบสุขสันติ ( Sorfware Developer & Qa Tester )
- 67159224 รัชภูมิ ธรรมประชา ( Software developer & Ui Designer )
- 67159844 ภูริภัทร ทองมวน ( Software developer & Ui Designer )

## หลักการและเหตุผล

- ปัจจุบันความต้องการอุปกรณ์คอมพิวเตอร์และเกมมิ่งเกียร์เติบโตขึ้นอย่างมาก แต่ผู้ซื้อมักเจอปัญหาร้านค้าออนไลน์ที่ใช้งานยากและจัดหมวดหมู่ซับซ้อน คณะผู้จัดทำจึงพัฒนาระบบ    E-commerce นี้ขึ้น เพื่อสร้างแพลตฟอร์มจำลองที่ซื้อขายง่าย ค้นหาสินค้าได้สะดวก และแยกหมวดหมู่อุปกรณ์ชัดเจน เพื่อตอบโจทย์พฤติกรรมของผู้บริโภคยุคดิจิทัลได้อย่างมีประสิทธิภาพ

## วัตถุประสงค์ของโครงงาน

- เพื่อพัฒนาเว็บแอปพลิเคชัน E-commerce สำหรับซื้อขายอุปกรณ์คอมพิวเตอร์ที่ค้นหาง่ายและแยกหมวดหมู่ชัดเจน
- เพื่อพัฒนาระบบตะกร้าสินค้าที่สามารถคำนวณเงิน ปรับเพิ่ม/ลดจำนวน และสรุปยอดสั่งซื้อได้อย่างถูกต้อง

## ขอบเขตของระบบ

**ผู้ใช้งาน**
- ลูกค้า
- ผู้ดูแลระบบ
- ผู้จัดการ

## ความสามารถของระบบ

**ลูกค้า (Customer)**
- สามารถสมัครสมาชิก เข้าสู่ระบบ และออกจากระบบได้
- สามารถค้นหาและดูรายละเอียดสินค้าตามหมวดหมู่ได้
- สามารถเพิ่มสินค้า แก้ไขจำนวน หรือลบสินค้าออกจากตะกร้าสินค้าได้
- สามารถสั่งซื้อสินค้าและชำระเงินผ่านระบบจำลอง (Simulation / Mock Payment) ได้
- สามารถติดตามสถานะคำสั่งซื้อและตรวจสอบประวัติการสั่งซื้อของตนเองได้

**ผู้ดูแลระบบ (Admin)**
- สามารถจัดการข้อมูลสินค้า ได้แก่ เพิ่ม แก้ไข ลบ และอัปเดตข้อมูลสินค้าได้
- สามารถจัดการข้อมูลหมวดหมู่สินค้าได้
- สามารถจัดการคำสั่งซื้อของลูกค้า และอัปเดตสถานะคำสั่งซื้อได้
- สามารถดูรายงานและ Dashboard สรุปข้อมูลเบื้องต้นของระบบได้

**ผู้จัดการระบบ (Super Admin)**
- สามารถจัดการข้อมูลสมาชิกทั้งหมด รวมถึงเพิ่ม แก้ไข ระงับ และลบบัญชีผู้ใช้งานได้
- สามารถจัดการสิทธิ์การใช้งานของผู้ดูแลระบบ (Admin) และผู้ใช้งาน (Customer) ได้
- สามารถเข้าถึงและใช้งานทุกความสามารถของผู้ดูแลระบบได้
- สามารถดูรายงานและ Dashboard ภาพรวมของระบบ เพื่อใช้ในการบริหารจัดการร้านค้าได้

## แนวทางการพัฒนาตาม SDLC

1. ประชุมเลือกหัวข้อ กำหนดขอบเขตระบบ และแบ่งงานในกลุ่ม
2. รวบรวมข้อมูลสินค้าและวิเคราะห์ความต้องการหน้าจอของระบบ
3. ออกแบบ UI/UX ด้วย Figma และออกแบบโครงสร้างฐานข้อมูล (Database Schema)
4. พัฒนา Frontend ด้วย React และพัฒนา Backend ด้วย Node.js เชื่อมต่อกับ MySQL
5. ทดสอบระบบแบบ
6. นำระบบขึ้นระบบจำลองหรือคลาวด์เซิร์ฟเวอร์
7. ตรวจสอบและแก้ไขข้อผิดพลาด

## เครื่องมือแล้วเทคโนโลยีที่ใช้

**Frontend**
- HTML/CSS/Javascript
- React
- Boostrap

**Backend**
- Node.js

**Database**
- Local Storage

**Design Tool**
- Figma

**Version Control**
- Github

## แนวทางในการทดสอบระบบ

**ประเภทการทดสอบ**
- User Acceptance Testing (UAT)
- 
## ผลลัพท์ที่คาดว่าจะได้รับ

1. ระบบสามารถแสดงรายการสินค้าและราคาอุปกรณ์คอมพิวเตอร์แยกตามหมวดหมู่ได้อย่างถูกต้อง
2. ระบบสามารถบันทึก ปรับปรุง และคำนวณราคาสินค้าในตะกร้าของลูกค้าได้แบบเรียลไทม์
3. ระบบสามารถจำลองการออกใบสรุปยอดเงินและประวัติการสั่งซื้อหลังสิ้นสุดขั้นตอนชำระเงิน
4. ข้อมูลการเลือกซื้อสินค้าถูกจัดเก็บใน Local Storage ได้อย่างถูกต้องและปลอดภัยฝั่งผู้ใช้

## แผนการดำเนินงาน

1. เก็บรวบรวมความต้องการของระบบ, ออกแบบ UI/UX ด้วย Figma และออกแบบโครงสร้างฐานข้อมูล (Database Schema)น Local Storage ได้อย่างถูกต้องและปลอดภัยฝั่งผู้ใช้
2. เขียนโค้ดส่วนหน้าบ้านด้วย React เพื่อสร้างหน้าจอแสดงสินค้า หมวดหมู่ ตะกร้าสินค้า และหน้าจำลองสั่งซื้อ
3. พัฒนาส่วนหลังบ้านด้วย Node.js และสร้างฐานข้อมูล MySQL เพื่อใช้จัดการและเชื่อมต่อข้อมูลสินค้าและคำสั่งซื้อ
4. ทำการทดสอบระบบแบบ Manual Testing และทำ UAT ตรวจสอบความถูกต้อง พร้อมจัดทำสรุปเพื่อนำเสนอผลงาน

## User Interface Design (Home Page)

ภาพหน้าหลักของระบบ E-Commerce สำหรับแสดงสินค้า หมวดหมู่ และเมนูหลักของเว็บไซต์

![Home Page](img/tech.jpg)

## Screenshot SourceTree 

![SourceTree](img/Sourcetree-commit.jpg)


## System Architecture

```mermaid
flowchart TB

%% ======================================
%% Users
%% ======================================

Customer[Customer]
Admin[Admin]
SuperAdmin[Super Admin]

%% ======================================
%% Presentation Layer
%% ======================================

subgraph Presentation["Presentation Layer"]
Frontend["React Frontend<br/>(User Interface)"]
end

%% ======================================
%% Application Layer
%% ======================================

subgraph Application["Application Layer (Express.js Backend)"]

Auth["Authentication Module"]

Product["Product Management"]

Cart["Shopping Cart"]

Order["Order Management"]

Payment["Payment Module"]

Warranty["Warranty Module"]

AdminModule["Administration Module"]

Upload["File Upload Module"]

end

%% ======================================
%% Data Layer
%% ======================================

subgraph Data["Data Layer"]

Database[("MySQL Database")]

Storage[("Uploads Folder<br/>Product Images")]

end

%% ======================================
%% Connections
%% ======================================

Customer --> Frontend
Admin --> Frontend
SuperAdmin --> Frontend

Frontend --> Auth
Frontend --> Product
Frontend --> Cart
Frontend --> Order
Frontend --> Payment
Frontend --> Warranty
Frontend --> AdminModule

Product --> Upload

Auth --> Database
Product --> Database
Cart --> Database
Order --> Database
Payment --> Database
Warranty --> Database
AdminModule --> Database

Upload --> Storage
Upload --> Database
```
## 1) แผนภาพกรณีการใช้งาน (Use Case Diagram)

![](img/UseCase.drawio%20(1).png)

หน้าที่ของแผนภาพ:
- แสดงขอบเขตของระบบ TechPulse ให้เห็นชัดว่าใครทำอะไรได้บ้าง
- ใช้ยืนยันขอบเขตงานกับสมาชิกในทีมและผู้สอน

ความสำคัญต่อการพัฒนาระบบ:
- ลดความเสี่ยงการตกหล่นฟังก์ชันสำคัญ เช่น ตรวจสิทธิ์และงานหลังบ้าน
- ใช้เป็นฐานในการกำหนดเส้นทางหน้าเว็บและสิทธิ์การเรียก API ตามบทบาท

## 2) แผนภาพคลาส (Class Diagram)

หมายเหตุ: แผนภาพนี้อ้างอิงชื่อโครงสร้างข้อมูลจริงในฐานข้อมูลของโครงการ

## Customer Purchase Flow

```mermaid
sequenceDiagram

autonumber

actor Customer

participant Frontend as React Frontend
participant ProductController
participant CartController
participant AddressController
participant OrderController
participant PaymentController
participant DB as MySQL Database

%% ==========================
%% Browse Products
%% ==========================

Customer->>Frontend: Browse Products

activate Frontend

Frontend->>ProductController: GET /products

activate ProductController

ProductController->>DB: Query Products

activate DB

DB-->>ProductController: Product List

deactivate DB

ProductController-->>Frontend: Return Products

deactivate ProductController

Frontend-->>Customer: Display Product List

deactivate Frontend

%% ==========================
%% View Product Detail
%% ==========================

Customer->>Frontend: Select Product

activate Frontend

Frontend->>ProductController: GET /products/{id}

activate ProductController

ProductController->>DB: Query Product Detail

activate DB

DB-->>ProductController: Product Detail

deactivate DB

ProductController-->>Frontend: Return Product Detail

deactivate ProductController

Frontend-->>Customer: Display Product Detail

deactivate Frontend

%% ==========================
%% Add to Cart
%% ==========================

Customer->>Frontend: Add to Cart

activate Frontend

Frontend->>CartController: POST /cart

activate CartController

CartController->>DB: Save Cart Item

activate DB

DB-->>CartController: Cart Updated

deactivate DB

CartController-->>Frontend: Cart Updated

deactivate CartController

Frontend-->>Customer: Display Shopping Cart

deactivate Frontend

%% ==========================
%% Checkout
%% ==========================

Customer->>Frontend: Checkout

activate Frontend

Frontend->>AddressController: GET /addresses

activate AddressController

AddressController->>DB: Retrieve Customer Addresses

activate DB

DB-->>AddressController: Address List

deactivate DB

AddressController-->>Frontend: Return Address List

deactivate AddressController

Frontend-->>Customer: Display Shipping Addresses

Customer->>Frontend: Select Shipping Address

Frontend->>OrderController: Submit addressId

activate OrderController

OrderController-->>Frontend: Address Valid

Frontend->>OrderController: Select Payment Method

OrderController-->>Frontend: Payment Method Accepted

deactivate OrderController

%% ==========================
%% Place Order
%% ==========================

Customer->>Frontend: Place Order

Frontend->>OrderController: Create Order

activate OrderController

OrderController->>DB: Insert Order

activate DB

DB-->>OrderController: Order ID

deactivate DB

loop For each Cart Item

OrderController->>DB: Insert Order Item

DB-->>OrderController: Success

end

%% ==========================
%% Payment
%% ==========================

OrderController->>PaymentController: Process Payment

activate PaymentController

PaymentController->>DB: Update Payment Status

activate DB

DB-->>PaymentController: Payment Completed

deactivate DB

alt Payment Success

PaymentController-->>OrderController: Payment Success

OrderController->>DB: Update Order Status

DB-->>OrderController: Paid

OrderController->>DB: Clear Shopping Cart

DB-->>OrderController: Cart Cleared

OrderController-->>Frontend: Order Completed

Frontend-->>Customer: Display Order Success

else Payment Failed

PaymentController-->>OrderController: Payment Failed

OrderController-->>Frontend: Display Payment Failed

Frontend-->>Customer: Retry Payment

end

deactivate PaymentController

deactivate OrderController

deactivate Frontend

```

---

### Warranty Claim Flow (Customer)

```mermaid
sequenceDiagram

autonumber

actor Customer

participant Frontend as React Frontend
participant WarrantyController
participant DB as MySQL Database

%% ======================================
%% View Order History
%% ======================================

Customer->>Frontend: View My Orders

activate Frontend

Frontend->>WarrantyController: GET /orders

activate WarrantyController

WarrantyController->>DB: Retrieve Customer Orders

activate DB

DB-->>WarrantyController: Order List

deactivate DB

WarrantyController-->>Frontend: Return Order List

Frontend-->>Customer: Display My Orders

deactivate WarrantyController

deactivate Frontend

%% ======================================
%% View Warranty
%% ======================================

Customer->>Frontend: View Warranty Information

activate Frontend

Frontend->>WarrantyController: GET /warranty/{orderId}

activate WarrantyController

WarrantyController->>DB: Retrieve Warranty Information

activate DB

DB-->>WarrantyController: Warranty Details

deactivate DB

WarrantyController-->>Frontend: Return Warranty Information

Frontend-->>Customer: Display Warranty Details

deactivate WarrantyController

deactivate Frontend

%% ======================================
%% Submit Warranty Claim
%% ======================================

Customer->>Frontend: Submit Warranty Claim

activate Frontend

Frontend->>WarrantyController: POST /warranty/claim

activate WarrantyController

WarrantyController->>DB: Save Warranty Claim

activate DB

DB-->>WarrantyController: Claim Created

deactivate DB

WarrantyController-->>Frontend: Warranty Claim Submitted

Frontend-->>Customer: Display Claim Success

deactivate WarrantyController

deactivate Frontend
```

---

### Manage Warranty Claim Flow (Admin)


```mermaid
sequenceDiagram

autonumber

actor Admin

participant Frontend as React Frontend
participant WarrantyController
participant DB as MySQL Database

%% ======================================
%% View Warranty Claims
%% ======================================

Admin->>Frontend: Open Warranty Claims

activate Frontend

Frontend->>WarrantyController: GET /warranty/claims

activate WarrantyController

WarrantyController->>DB: Retrieve Warranty Claims

activate DB

DB-->>WarrantyController: Warranty Claim List

deactivate DB

WarrantyController-->>Frontend: Return Claim List

Frontend-->>Admin: Display Warranty Claims

deactivate WarrantyController

deactivate Frontend

%% ======================================
%% View Claim Detail
%% ======================================

Admin->>Frontend: Select Warranty Claim

activate Frontend

Frontend->>WarrantyController: GET /warranty/claims/{claimId}

activate WarrantyController

WarrantyController->>DB: Retrieve Claim Detail

activate DB

DB-->>WarrantyController: Claim Detail

deactivate DB

WarrantyController-->>Frontend: Return Claim Detail

Frontend-->>Admin: Display Claim Detail

deactivate WarrantyController

deactivate Frontend

%% ======================================
%% Review Warranty Claim
%% ======================================

Admin->>Frontend: Review Warranty Claim

activate Frontend

Frontend->>WarrantyController: Update Claim Status

activate WarrantyController

alt Claim Approved

WarrantyController->>DB: Update Status = Approved

activate DB

DB-->>WarrantyController: Update Successful

deactivate DB

WarrantyController-->>Frontend: Claim Approved

Frontend-->>Admin: Display Approval Success

else Claim Rejected

WarrantyController->>DB: Update Status = Rejected

activate DB

DB-->>WarrantyController: Update Successful

deactivate DB

WarrantyController-->>Frontend: Claim Rejected

Frontend-->>Admin: Display Rejection Success

end

deactivate WarrantyController

deactivate Frontend
```

---

### Admin Add Product Flow

```mermaid
sequenceDiagram

autonumber

actor Admin

participant Frontend as React Frontend
participant ProductController
participant UploadModule
participant DB as MySQL Database
participant Storage as Uploads Folder

%% ======================================
%% Open Product Management
%% ======================================

Admin->>Frontend: Open Product Management

activate Frontend

Frontend->>ProductController: GET /products

activate ProductController

ProductController->>DB: Retrieve Product List

activate DB

DB-->>ProductController: Product List

deactivate DB

ProductController-->>Frontend: Return Product List

Frontend-->>Admin: Display Product List

deactivate ProductController

deactivate Frontend

%% ======================================
%% Add New Product
%% ======================================

Admin->>Frontend: Add New Product

activate Frontend

Frontend->>ProductController: Enter Product Information

activate ProductController

%% ======================================
%% Upload Image
%% ======================================

Frontend->>UploadModule: Upload Product Image

activate UploadModule

UploadModule->>Storage: Save Image File

activate Storage

Storage-->>UploadModule: Upload Successful

deactivate Storage

UploadModule-->>ProductController: Return Image Path

deactivate UploadModule

%% ======================================
%% Save Product
%% ======================================

ProductController->>DB: Save Product Information

activate DB

DB-->>ProductController: Product Created

deactivate DB

ProductController-->>Frontend: Product Created Successfully

Frontend-->>Admin: Display Success Message

deactivate ProductController

deactivate Frontend
```

---

### Admin Manage Order Flow

```mermaid
sequenceDiagram

autonumber

actor Admin

participant Frontend as React Frontend
participant ProductController
participant UploadModule
participant Storage as Uploads Folder
participant DB as MySQL Database

%% ==========================================
%% Open Product Management
%% ==========================================

Admin->>Frontend: Open Product Management

activate Frontend

Frontend->>ProductController: Request Product List

activate ProductController

ProductController->>DB: Retrieve Products

activate DB

DB-->>ProductController: Product List

deactivate DB

ProductController-->>Frontend: Return Product List

Frontend-->>Admin: Display Product Management Page

deactivate ProductController

deactivate Frontend

%% ==========================================
%% Add New Product
%% ==========================================

Admin->>Frontend: Click Add Product

activate Frontend

Frontend-->>Admin: Display Product Form

Admin->>Frontend: Enter Product Information

%% ==========================================
%% Upload Image
%% ==========================================

Admin->>Frontend: Select Product Image

Frontend->>UploadModule: Upload Image

activate UploadModule

UploadModule->>Storage: Save Image File

activate Storage

Storage-->>UploadModule: Image Saved

deactivate Storage

UploadModule-->>Frontend: Return Image Path

deactivate UploadModule

%% ==========================================
%% Save Product
%% ==========================================

Frontend->>ProductController: Submit Product Data

activate ProductController

ProductController->>DB: Save Product Information

activate DB

DB-->>ProductController: Product Created

deactivate DB

ProductController-->>Frontend: Return Success

Frontend-->>Admin: Display Product Created Successfully

deactivate ProductController

deactivate Frontend
```

หน้าที่ของแผนภาพ:
- แสดงโครงสร้างข้อมูลหลักและความสัมพันธ์ระหว่างเอนทิตีในระบบ
- ใช้อ้างอิงร่วมกันระหว่างการออกแบบฐานข้อมูลและการพัฒนาโมเดล

ความสำคัญต่อการพัฒนาระบบ:
- ลดความกำกวมของข้อมูล เช่น ความสัมพันธ์ Order กับ OrderItem และ Payment
- ป้องกันการออกแบบซ้ำซ้อน ทำให้พัฒนา Controller และ Service ได้สอดคล้องกัน

## 3) แผนภาพลำดับงาน (Sequence Diagram)

กรณีศึกษา: ลำดับการทำงานของการสั่งซื้อและการชำระเงินในระบบจริง

```mermaid
sequenceDiagram

autonumber

actor Customer

participant Frontend as React Frontend
participant ProductController
participant CartController
participant OrderController
participant PaymentController
participant DB as MySQL Database

%% ==========================
%% Browse Products
%% ==========================

Customer->>Frontend: Browse Products

activate Frontend

Frontend->>ProductController: GET /products

activate ProductController

ProductController->>DB: Query Products

activate DB

DB-->>ProductController: Product List

deactivate DB

ProductController-->>Frontend: Return Products

deactivate ProductController

Frontend-->>Customer: Display Product List

deactivate Frontend

%% ==========================
%% View Product Detail
%% ==========================

Customer->>Frontend: Select Product

activate Frontend

Frontend->>ProductController: GET /products/{id}

activate ProductController

ProductController->>DB: Query Product Detail

activate DB

DB-->>ProductController: Product Detail

deactivate DB

ProductController-->>Frontend: Return Product Detail

deactivate ProductController

Frontend-->>Customer: Display Product Detail

deactivate Frontend

%% ==========================
%% Add to Cart
%% ==========================

Customer->>Frontend: Add to Cart

activate Frontend

Frontend->>CartController: POST /cart

activate CartController

CartController->>DB: Save Cart Item

activate DB

DB-->>CartController: Cart Updated

deactivate DB

CartController-->>Frontend: Cart Updated

deactivate CartController

Frontend-->>Customer: Display Shopping Cart

deactivate Frontend

%% ==========================
%% Checkout
%% ==========================

Customer->>Frontend: Checkout

activate Frontend

Frontend->>OrderController: Submit Shipping Address

activate OrderController

OrderController-->>Frontend: Address Valid

Frontend->>OrderController: Select Payment Method

OrderController-->>Frontend: Payment Method Accepted

deactivate OrderController

%% ==========================
%% Place Order
%% ==========================

Customer->>Frontend: Place Order

Frontend->>OrderController: Create Order

activate OrderController

OrderController->>DB: Insert Order

activate DB

DB-->>OrderController: Order ID

deactivate DB

loop For each Cart Item

OrderController->>DB: Insert Order Item

DB-->>OrderController: Success

end

%% ==========================
%% Payment
%% ==========================

OrderController->>PaymentController: Process Payment

activate PaymentController

PaymentController->>DB: Update Payment Status

activate DB

DB-->>PaymentController: Payment Completed

deactivate DB

alt Payment Success

PaymentController-->>OrderController: Payment Success

OrderController->>DB: Update Order Status

DB-->>OrderController: Paid

OrderController->>DB: Clear Shopping Cart

DB-->>OrderController: Cart Cleared

OrderController-->>Frontend: Order Completed

Frontend-->>Customer: Display Order Success

else Payment Failed

PaymentController-->>OrderController: Payment Failed

OrderController-->>Frontend: Display Payment Failed

Frontend-->>Customer: Retry Payment

end

deactivate PaymentController

deactivate OrderController

deactivate Frontend
```

หน้าที่ของแผนภาพ:
- แสดงลำดับการเรียกใช้งานจริงจากผู้ใช้ไปจนถึงฐานข้อมูล
- ช่วยให้ทีมเห็นจุดที่ต้องมีการตรวจสอบสิทธิ์ ตรวจสต็อก และควบคุมธุรกรรม

ความสำคัญต่อการพัฒนาระบบ:
- ทำให้มองเห็นจุดเสี่ยงด้านความถูกต้องของข้อมูล เช่น การตัดสต็อกซ้ำ
- ใช้ระบุจุดคอขวดที่ทำให้ระบบช้าในช่วงผู้ใช้หนาแน่น
