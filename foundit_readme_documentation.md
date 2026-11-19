FoundIt! - Campus Lost & Found Portal

**FoundIt!** is a responsive, single-page web application interface designed to streamline the reporting, tracking, and claiming of lost and found items across a university campus. Developed for the **IMS566 (Advanced Web Design Development and Content Management)** individual assignment, this prototype demonstrates modern UI/UX design principles, client-side state management, and interactive data visualization.

---

## Features Included

* **Simulated Authentication System (Login & Registration):** 
  * Features a clean tabbed interface allowing users to log in with pre-configured credentials or register a new student account stored via `localStorage`.
  * Includes real-time validation and clear error alert feedback for invalid credentials or duplicate emails.
* **Responsive Navigation Menu & Theme Switcher:** 
  * Features a collapsible sidebar navigation menu on desktop and a mobile-friendly top header drawer on smaller screens.
  * Includes a **Light Mode (White & Gold)** and **Dark Mode (Black & Gold)** theme toggle that dynamically updates the UI and chart styling.
* **Interactive Analytics Dashboard:** 
  * Displays real-time summary metrics: *Total Reports*, *Active Lost Items*, *Items Claimed*, and overall *Recovery Rate (%)*.
  * Provides automated **Quick Insights** highlighting the top missing item category and the most recently reported item.
* **Meaningful Data Visualization:** 
  * Integrates an interactive **Chart.js Pie Chart** breaking down active lost items by campus location (*Main Library, Cafeteria, Lecture Halls, Sports Complex, and Bus Stop*), updating dynamically as items are added, edited, or claimed.
* **Dual Data View Pages (CRUD Functionality):**
  1. **Lost Items Board (Card Grid View):** Displays active lost items with category icons, descriptions, locations, and dates. Users can **Report** new found items, **Edit** existing item details, **Delete** entries, or **Claim** an item using a Student Matric ID.
  2. **Claims History (Structured Table View):** Automatically logs all resolved/claimed items in a responsive table, displaying the Item ID, description, category, claimant's Matric ID, return date, and resolution status.

---

## Instructions to Test Login & Features

1. **Launch the Application:** Open `index.html` (or `FoundIt_white_gold.html`) in **Google Chrome** or visit the live GitHub Pages URL.
2. **Default Login Credentials:** The login form is pre-filled for convenience, or you can enter the following credentials manually:
   * **Student Email:** `student@uitm.edu.my`
   * **Password:** `password123`
3. **Test Error Handling:** Try entering an incorrect password to view the validation alert banner, or switch to the **Register** tab to create a new local account.
4. **Explore & Test CRUD Operations:**
   * Navigate to the **Lost Items Board** via the left sidebar.
   * Click **+ Report Found Item** to add a new item and watch the Dashboard statistics and Pie Chart update automatically.
   * Click **Claim Item** on any card (pre-filled with Matric ID `2026123456` for quick testing) to move the item into the **Claims History** table.
   * Toggle **Dark Mode** in the bottom-left sidebar to switch between the White & Gold and Black & Gold themes.

---

## Frameworks, Libraries & Technologies Used

* **HTML5 & CSS3:** Semantic structure, custom CSS variables for theming, and smooth keyframe transitions.
* **JavaScript (ES6+):** DOM manipulation, `localStorage` authentication handling, and dynamic CRUD state management.
* **[Bootstrap 5.3.0](https://getbootstrap.com/):** Responsive grid system, modals, nav pills, cards, and utility classes.
* **[Bootstrap Icons 1.10.5](https://icons.getbootstrap.com/):** Vector iconography across navigation, badges, and item categories.
* **[Chart.js](https://www.chartjs.org/):** Interactive, responsive data visualization for campus location analytics.
* **[Google Fonts](https://fonts.google.com/):** *Playfair Display* for headings and *DM Sans* for clean, legible body copy.
