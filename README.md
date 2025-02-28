# Car-Detail-and-Modeling-Analysis

This Power BI dashboard provides insights into **car service payments, appointments, employee performance, and revenue trends**. It helps analyze key business metrics such as total revenue, payment methods, and service duration.

## **Data Sources**
The dashboard uses data from:
- Customer appointments and service details
- Payment transactions (amount paid, payment method, status)
- Employee performance data

### **Database** - carbusinessdb
### **Tables**
- appointments - (appointment_id, customer_id, vehicle_id, service_id, employee_id, appointment_date, appointment_status, payment_id) 
- customers - (customer_id, first_name, last_name, email, phone_number, address, vehicle_id, joined_date )
- employees - (employee_id, first_name, last_name, employee_role, phone_number, email, salary, join_date)
- inventory - (inventory_id, product_name, category, quantity, cost_price, selling_price, supplier_id)
- payments - (payment_id, payment_method, payment_status, amount_paid, payment_date)
- services - (service_id, service_name, price, duration_minutes)
- suppliers - (supplier_id, supplier_name, contact_person, phone_number, email, address)
- vehicles - (vehicle_id, customer_id, make, model, year, license_plate, vin_number)

## **Dashboard Features & Insights**
### **1️⃣ Revenue Analysis**
- Displays **total revenue** generated.
- Tracks **sum of amount paid per year**.

### **2️⃣ Appointments & Services**
- Shows **total count of appointments**.
- Tracks **customer count by year**.

### **3️⃣ Payment Methods Breakdown**
- Pie chart showing **different payment methods used** (Credit Card, Cash, PayPal, etc.).
- Helps in understanding preferred payment options.

### **4️⃣ Revenue Per Employee**
- Bar chart showing **which employees generated the most revenue**.

### **5️⃣ Revenue Trends**
- A line graph showing **fluctuations in revenue** over time.

### **6️⃣ Service Duration Analysis**
- Bar chart showing the **average service duration by service type**.

### **7️⃣ Employee Performance**
- Analyzes **employee efficiency** based on completed appointments.

## **How to Use the Dashboard**
1. Open **Power BI Desktop**.
2. Load the MySQL database `carbusinessdb` .
3. Click **Refresh** to update the data.
4. Interact with the filters to explore revenue trends, payment methods, and employee performance.
