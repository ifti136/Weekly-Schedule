Optimal Life Balance Schedule
This project is a dynamic, responsive weekly schedule planner designed to optimize time allocation across university studies, health routines (workout and personal care), and religious obligations (Namaj).

Built as a single-page application using modern front-end technologies delivered via CDNs, it requires zero installation or build steps, making it incredibly easy to host and run.

✨ Features
Dynamic Time Configuration: Easily set custom times for all five daily Namaj prayers (Fajr, Zuhr, Asr, Maghrib, Isha) and daily University/Out-of-Home blocks (Sun-Thu).

Instant Visual Updates: The schedule automatically updates cell content (Namaj times) and applies visual highlighting (University blocks) based on user input in the settings panel.

Weekly Routine Breakdown: Comprehensive daily schedule from 5:00 AM to 10:15 PM.

Workout Modals: Clickable buttons next to workout blocks reveal the specific routine and exercises for that day.

Responsive Design: Optimized for viewing on both mobile devices and desktops.

🚀 Getting Started (Zero Setup)
Since this application leverages CDNs for all its dependencies (React, Babel, and Tailwind CSS), it runs directly from the HTML file in any modern browser.

Clone the Repository:

git clone [https://github.com/YourUsername/Optimal-Life-Schedule-App.git](https://github.com/YourUsername/Optimal-Life-Schedule-App.git)
cd Optimal-Life-Schedule-App

Run the App:
Simply open the index.html file in your preferred web browser:

open index.html
# or start a simple local server if preferred
python3 -m http.server

The application will load instantly, ready for use.

💻 Technologies Used
HTML5: Core structure.

React (via CDN): Used for component-based architecture and state management, enabling the dynamic updates to the schedule.

Babel (via CDN): Compiles JSX directly in the browser.

Tailwind CSS (via CDN): Provides modern, utility-first styling for a clean and responsive UI.

⚙️ Customization
Open the "Dynamic Schedule Settings" section at the top of the schedule to personalize:

Namaj Times: Adjust the 24-hour time slots to match your local prayer schedule.

University Block: Set the Start Time and End Time for each day you are scheduled to be away from home (e.g., at university). The corresponding time slots in the table will be highlighted in red.
