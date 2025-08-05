# 🩸 Blood Bank & Donation Management System

A frontend-based project that simulates a blood bank management system using **HTML**, **CSS**, **JavaScript**, and **Excel (as a pseudo-database)** via the **SheetJS** library.

This project enables:
- 🧑‍💻 Donor registration
- 🩸 Acceptor blood request submissions
- 📊 Blood inventory visualization
- 📁 Data stored/updated in an Excel file (`data.xlsx`)

---

## 🚀 Features

- **Donor Registration**  
  Users can register by entering their name, age, blood group, and contact info.

- **Blood Request (Acceptor)**  
  Individuals can request blood by specifying their name, required blood group, and contact number.

- **Live Inventory View**  
  View the currently available units of each blood group from the Excel file.

- **Excel as a Database**  
  Data is saved and retrieved using the `SheetJS` library to read/write to Excel (`.xlsx`) files.

---

## 🧰 Technologies Used

| Technology | Purpose                         |
|------------|----------------------------------|
| HTML       | Page structure                  |
| CSS        | Styling and layout              |
| JavaScript | Form logic and Excel handling   |
| SheetJS    | Read/write Excel files          |
| Excel      | Mock database (`data.xlsx`)     |

---

## 📁 Project Structure


---

## 🔧 How to Use

1. Clone or download this repository.
2. Open `index.html` in your browser.
3. Use navigation buttons to:
   - Register as a donor (`donor.html`)
   - Request blood (`acceptor.html`)
   - View blood stock (`inventory.html`)
4. Data will be handled via the `data.xlsx` file.

> ⚠️ Due to browser restrictions, direct Excel file writing is not fully supported in all browsers. After form submission, the updated file will be downloaded — you can manually replace `data.xlsx` with the new version.

---

## 📦 Excel File Structure

### Sheet: `Donors`
| Name | Age | BloodGroup | Contact |
|------|-----|------------|---------|

### Sheet: `Acceptors`
| Name | BloodGroup | Contact |
|------|------------|---------|

### Sheet: `Inventory`
| BloodGroup | UnitsAvailable |
|------------|----------------|

---

## 💡 Future Improvements

- Integrate a real backend (Node.js, Flask, etc.)
- Use a real database like Firebase, MongoDB, or MySQL
- Authentication for admins
- Real-time inventory updates

---

## 👨‍💻 Author

**Srivarsha Akula**  
Frontend Developer | Project Designer

---

## 📄 License

This project is open-source and free to use under the MIT License.
