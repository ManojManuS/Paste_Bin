# Paste_Bin
paste_Bin_Project
# Project Description
This project is a client-side Pastebin-style web application that allows an admin to create text pastes and generate shareable links. Users can open these links to view the pasted content, and each view is automatically counted. The admin panel provides options to view statistics and delete existing pastes.
The entire application works using the browser’s LocalStorage, without any backend or database.
# Features
 1.Create text pastes from the admin panel
 2.Generate unique, shareable links
 3.View pasted content on a separate user page
 4.Automatic view counter for each paste
 5.Delete existing pastes from admin panel
 6.Data stored using browser LocalStorage
 7.No backend or server required.

# Technologies Used
 1.HTML5 – Structure and markup
 2.CSS3 – Basic styling and layout
 3.JavaScript (ES6) – Logic, DOM manipulation, LocalStorage handling.

# Versions Used
HTML: HTML5
CSS: CSS3
JavaScript: ECMAScript 6 (ES6)
Browser Storage: Web Storage API (LocalStorage).

# Project Structure
/pastebin-project
│
├── admin.html     # Admin panel to create, view, and delete pastes
├── user.html      # User page to view pasted content and count views
└── README.md      # Project documentation

# How to Use
Open admin.html in a browser(UserId: Manoj S, Password: Manojs123).
Enter text and click Convert Link.
Open the generated link to view the paste.
Refresh admin page to see updated view count.
Use the Delete button to remove any paste.

# Future Enhancements
Backend integration (Node.js / PHP)
Database support (MySQL / MongoDB)
User authentication
Expiry time for pastes
Spam protection for view counts

# Output
<img width="1366" height="729" alt="Screenshot (83)" src="https://github.com/user-attachments/assets/e7984fab-1c63-4e29-866c-da4043544491" />
Image1:Here the option if person is Admin or user.

<img width="1366" height="729" alt="Screenshot (85)" src="https://github.com/user-attachments/assets/18501b88-4c98-49c4-acbc-a0d509060bb2" />
Image2:If a person admin, having a userid and password(Mentioned in above).
Here it displayed invalid password and userid which have enter by admin

<img width="1366" height="727" alt="Screenshot (86)" src="https://github.com/user-attachments/assets/777cfc8b-3a0d-40fd-a733-5231f0271880" />
Image3: Here admin entering without giving a userid and password it showing alert message to enter userid and password.

<img width="1366" height="725" alt="Screenshot (87)" src="https://github.com/user-attachments/assets/1a853d10-56e2-490e-bc81-47a37fb96490" />
Image4:After successfuly entering userid and password admin entered to admin panel.

<img width="1366" height="725" alt="Screenshot (88)" src="https://github.com/user-attachments/assets/b06140c3-8e94-448f-919f-1844744be61f" />
Image5:Admin created a link by pasting or written something in blanck space and then converted into link using "Click to convert link"button.

<img width="1366" height="723" alt="Screenshot (89)" src="https://github.com/user-attachments/assets/38c0ee3b-0ae9-4566-9496-ed8ad1756a5c" />
Image6:It's a User side panel to view content by pasting link on the given space by clicking on open button its display the content which is pasted by Admin.

<img width="1366" height="723" alt="Screenshot (90)" src="https://github.com/user-attachments/assets/28191328-ece4-4f11-b783-fdd8de5df984" />
Image7:In this admin is deleting existing link by clicking Delete button with display confirmantion alert message.

<img width="1366" height="723" alt="Screenshot (91)" src="https://github.com/user-attachments/assets/6e1e13b9-2e7a-4993-8389-1418389998ea" />
Image8:Here user try to view deleted link it showing invalid link or deleted link you have pasted to user.


 
