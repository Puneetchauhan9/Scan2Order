# 🍽️ Scan2Order — Oracle APEX-Based Restaurant Ordering System

**Scan2Order** is a QR-code-powered restaurant ordering system built with **Oracle APEX**, allowing customers to scan a table-specific QR code and access a dynamic digital menu to place orders directly from their seats.

---

## 🔥 Features

- ✅ **QR Code Scanning** — Each table has a unique QR code to open a menu specific to that table.
- ✅ **Dynamic Menu Display** — Items shown based on categories, availability, and restaurant logic.
- ✅ **Cart Management** — Add/remove items before confirming the order.
- ✅ **Order Placement** — Sends order directly to billing counter.
- ✅ **Admin Panel** — For adding/updating tables, menu items, prices, and managing orders.
- ✅ **Responsive Design** — Mobile and tablet friendly UI.

---

## 🛠️ Tech Stack

| Layer            | Technology              |
|------------------|--------------------------|
| Frontend         | Oracle APEX (v24.1), HTML, CSS, JavaScript |
| Backend          | PL/SQL, Oracle Database |
| Deployment Ready | Oracle Cloud / Self-hosted APEX |
| Version Control  | Git + GitHub            |

---

## 📦 How to Deploy

1. **Import SQL File**  
   - Use `scan2order_apex.sql` in your Oracle APEX workspace.

2. **Create Supporting Tables**  
   - Menu Table
   - Orders Table
   - Table Master (for mapping QR codes)

3. **Customize QR Codes**  
   - Use a free QR generator and link to:  
     ```
     https://apex.oracle.com/pls/apex/<workspace_alias>/r/scan2order/menu?page=1&table_id=XYZ
     ```

4. **Assign Roles**  
   - Admin: Manage menus & tables  
   - Customer: Access via QR to place orders

---

## 📸 Screenshots

*Add screenshots of:*
- Landing Page
- QR Scan Result → Menu View
- Admin Dashboard
- Order History

---


---

## 👨‍💻 Author

**Puneet Chauhan**  
- 💼 B.Tech Computer Science | Oracle APEX Developer  
- 📧 PC3622433@GMAIL.COM  
- 🌐 [LinkedIn](www.linkedin.com/in/puneet-chauhan-600138253) 

---


---

## 🙌 Support & Contribution

If you'd like to suggest improvements, create issues or submit PRs.  
Reach out if you’d like to collaborate on APEX projects!




