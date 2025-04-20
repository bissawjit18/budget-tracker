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

⬇️Testing Instructions 

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


Notes

Data is stored in the browser's local storage. Clearing storage will reset expenses and settings.
For production, consider hosting on platforms like Netlify or GitHub Pages.
If you encounter issues with Node.js setup, a pre-generated styles.css can be provided.

