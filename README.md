# **Registation Form with Local storage :**

Deployed Link : https://registration-form-8rw4.onrender.com

**Project Overview:**
This project is a basic registration form that users can fill out. The information they submit is stored locally, and the entered details are displayed in a table.

**HTML (index.html):**
- The HTML file defines the structure of the web page.
- There's a form with fields for the user's name, email, password, date of birth, and a checkbox to accept terms and conditions.
- Entries are displayed in a table below the form.

**Tailwind CSS:**
- Tailwind CSS is a utility-first CSS framework that helps style the HTML elements.
- It's added to make the form and entries visually appealing.

**JavaScript (index.js):**
1. **Retrieving Entries:**
   - When the page loads, it checks if there are previously stored user entries in the local storage.
   - If entries are found, they are retrieved and parsed; otherwise, an empty array is created.

2. **Displaying Entries:**
   - A function formats the user entries into an HTML table.
   - The table is dynamically updated on the page to show the user submissions.

3. **Saving User Form Submission:**
   - When a user submits the registration form, an event listener is triggered.
   - The entered information (name, email, password, date of birth, and acceptance of terms) is collected.
   - A new entry object is created with this information.
   - The entry is added to the array of user entries, and the array is saved back to local storage.
   - The display function is called to update the displayed entries.

4. **Event Listeners:**
   - An event listener is set up to watch for form submissions.
   - When the form is submitted, the `saveUserForm` function is called.

5. **Initializing:**
   - The `displayEntries` function is called on page load to show any existing entries.
<img width="959" alt="image" src="https://github.com/Prathibha-yadav/RegistrationForm/assets/126705101/1737eaf1-aede-457f-a126-24c0e0239f4c">

