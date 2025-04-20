Expense Tracker
A simple web app to track daily expenses with features like adding, editing, filtering, exporting to CSV, printing, monthly reports, default light mode, and a user guide modal.
Setup Instructions

Install Node.js: Ensure Node.js is installed on your system. Download it from nodejs.org if needed.
Clone or Download: Download or clone this project folder.
Install Dependencies:
Open a terminal in the project folder.
Run: npm install


Build CSS:
Run: npm run build to generate styles.css.
For development, run: npm run watch to automatically rebuild CSS on changes.


Run the App:
Open index.html in a web browser.
Alternatively, use a local server (e.g., npx serve or VS Code Live Server) for better testing.



Project Structure

index.html: Main HTML file with the app's structure and logic.
input.css: Input CSS file with Tailwind directives and custom styles.
styles.css: Generated CSS file (do not edit directly).
tailwind.config.js: Tailwind CSS configuration file.
package.json: Node.js project metadata and scripts.
README.md: Project setup and testing instructions.

Features

Add, edit, and delete expenses.
Filter expenses by date or category.
Export expenses to CSV.
Print expense list.
View monthly expense reports.
Default Light Mode: The app opens in light mode by default, ignoring the browser's prefers-color-scheme. Users can toggle to dark mode, and the preference is saved.
User Guide Modal: A user guide modal appears on the first visit, explaining how to use the app. It can be reopened using the "ব্যবহার বিধি" button.
Dark mode support.
Responsive design for mobile and desktop.

Testing Instructions

Default Light Mode:

Clear local storage (Developer Tools > Application > Storage > Local Storage > Clear).
Reload the page and verify the app opens in light mode (background should be light, theme icon should be 🌙).
Click the theme toggle button to switch to dark mode and back, ensuring the icon changes (🌙 ↔ ☀️).
Reload the page to confirm the saved theme is applied.


User Guide Modal:

Clear local storage to simulate first visit.
Reload the page and verify the user guide modal appears automatically.
Close the modal using the "বন্ধ করুন" button and reload to ensure it doesn't reappear.
Click the "ব্যবহার বিধি" button to reopen the modal.
Test on mobile and desktop to ensure the modal is responsive and scrollable.


Other Features:

Add an expense and verify it appears in the table (desktop) and cards (mobile).
Edit and delete expenses to ensure functionality.
Test filtering by date and category.
Export expenses to CSV and verify the file contents.
Print the expense list and check the output.
Generate a monthly report by selecting a month.


Browser Compatibility:

Test in Brave (disable Shields for local storage), Chrome, Firefox, and Safari.
Check console logs for errors (F12 > Console).



Debugging Tips

Dark Mode Issues:

Check console for errors (e.g., "Error toggling theme").
Clear local storage and verify default light mode.
Ensure styles.css is generated (npm run build).
In Brave, disable Shields temporarily.


User Guide Modal Issues:

Check console for errors (e.g., "Error showing user guide modal").
Clear local storage to test first-time modal display.
Verify the "ব্যবহার বিধি" button works.


General Issues:

Ensure Node.js is installed and npm install was successful.
Run npm run build if styles are missing.
Check console logs for any JavaScript errors.



Notes

Data is stored in the browser's local storage. Clearing storage will reset expenses and settings.
For production, consider hosting on platforms like Netlify or GitHub Pages.
If you encounter issues with Node.js setup, a pre-generated styles.css can be provided.

