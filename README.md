Amity University Lost & Found Portal <br>
A modern Lost & Found Portal designed for Amity University Bangalore to help the campus community report and track lost or found items securely and efficiently.
This repository currently contains the Login Page implementation — the entry point for all users.

📚 Background<br>
Every year, countless items are misplaced within the campus premises. Traditional lost-and-found desks are often unorganized and time-consuming.
This portal aims to digitize the process, providing:

Quick reporting of lost items

Easy searching for found items

Secure authentication for all users

A centralized database for item management

🎯 Objectives<br>
Reduce time taken to match lost and found items

Ensure security through verified login

Improve accessibility with a responsive, web-based interface

✨ Features<br>
✅ Responsive UI — works on desktop, tablet, and mobile<br>
✅ Custom form validation for accurate input data<br>
✅ Show/Hide password toggle for user convenience<br>
✅ CAPTCHA-style bot check<br>
✅ Social login buttons (Google & GitHub placeholders)<br>
✅ "Remember Me" functionality for repeat users<br>
✅ Minimal & modern design using gradients, shadows, and Google Fonts<br>

🛠️ Tech Stack<br>
Technology	Purpose<br>
HTML5	Page structure<br>
CSS3	Styling, layout, and responsiveness<br>
JavaScript (Vanilla)	Client-side logic and validation<br>
Google Fonts	Typography<br>
Icons8	Icons for buttons and UI<br>

📂 Folder Structure<br>

bash<br>
Copy<br>
Edit<br>
📦 lost_found_portal_team7 <br>
 ┣ 📜 index.html         # Login page UI & JS validation <br>
 ┣ 📜 amity-logo.jpg     # University logo<br>
 ┣ 📜 screenshot1.png    # Full login page screenshot<br>
 ┣ 📜 screenshot2.png    # Password toggle example<br>
 ┣ 📜 screenshot3.png    # Validation error message example <br>
 ┗ 📜 README.md          # Documentation<br>
🚀 How to Run<br>
1️⃣ Clone the repository<br>

bash<br>
Copy<br>
Edit<br>
git clone https://github.com/Yamuna6375/lost_found_portal_team7.git <br>
2️⃣ Navigate to the folder <br>


bash<br>
Copy<br>
Edit<br>
cd lost_found_portal_team7 <br>
3️⃣ Open the HTML file<br>

bash<br>
Copy<br>
Edit<br>
start index.html     # Windows <br>  
open index.html      # Mac  <br>
xdg-open index.html  # Linux  <br>
🔍 Form Validation Rules<br>
Field	Rule	Example<br>
University Email / ID	Cannot be empty	example@amity.edu <br>
SEN Number	Format: A866####	A8661234*** <br>
Phone Number	Must be exactly 10 digits	9876543210 <br>
Password	Cannot be empty	******** <br>
CAPTCHA Check	"I am not a robot" must be ticked	✅<br>

📷 Screenshots<br>
<img width="1362" height="613" alt="image" src="https://github.com/user-attachments/assets/9977492b-d6cf-453d-ac92-b42ebb8815bd" /><br>
<img width="1363" height="245" alt="image" src="https://github.com/user-attachments/assets/e6e606b4-3966-4e0d-b0ab-a52d089ce2db" /><br>

 
🔄 How It Works<br>
User enters login credentials — University ID, SEN number, phone, and password.

JavaScript validation checks:

All fields are filled

SEN follows the A866#### format

Phone number is 10 digits

CAPTCHA is checked

If valid, the form submits (future versions will connect to backend authentication).

If invalid, an error message is shown instantly without reloading the page.

📌 Future Scope<br>
🔹 Integration with Amity University SSO

🔹 Backend database to store user sessions and items

🔹 Dashboard to view lost & found reports

🔹 Image upload feature for found/lost items

🔹 Search & filter functionality for easier matching

🤝 Contributors<br>
Name	Role<br>
Yamuna	Frontend Development & UI Design<br>
Team 7 Members	Concept, Validation Rules, and Testing<br>
✍️ Author<br>

Project Lead & Frontend Developerbr>

Name: Yamuna

Email: yamuna@s.amity.edu

Phone: +91-6363752562

GitHub: Yamuna6375


