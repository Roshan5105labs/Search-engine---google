
# Search Engine - Google Clone

A front-end implementation of Google Search, developed as **Project 0** for **CS50's Web Programming with Python and JavaScript**.

## 📖 Description
This project recreates the visual design and core functionality of Google Search using pure **HTML** and **CSS**. It allows users to perform real queries that redirect to Google's servers, functioning exactly like the actual search engine.

## 📂 Files Included

### 1. `index.html` (Main Search Page)
* **Functionality:** The main landing page with the standard Google search bar.
* **Features:**
    * Includes a "Google Search" button and an "I'm Feeling Lucky" button.
    * "I'm Feeling Lucky" (`name="btnI"`) redirects directly to the first search result.
    * Links to **Image Search** and **Advanced Search** in the top-right corner.
    * Links to "About" and "Store" in the top-left corner.

### 2. `Image_Search.html` (Google Images)
* **Functionality:** A specialized search page for finding images.
* **Features:**
    * Includes a hidden input (`name="tbm" value="isch"`) to ensure the query is sent to Google Images specifically.
    * Maintains the Google aesthetic with a "images" label under the logo.
    * Allows easy navigation back to the main search page.

### 3. `Advanced_Search.html` (Advanced Querying)
* **Functionality:** A form that allows users to filter search results with specific criteria.
* **Parameters Implemented:**
    * **All these words:** `as_q`
    * **This exact word or phrase:** `as_epq`
    * **Any of these words:** `as_oq`
    * **None of these words:** `as_eq`
    * **Numbers ranging from:** `as_nlo` to `as_nhi`
* **Design:**
    * Stacked vertical layout with left-aligned labels and instructions.
    * Blue "Advanced Search" submission button.

### 4. `stylesheet.css`
* **Styling:** Custom CSS to mimic Google's 2015 aesthetic.
* **Responsive Design:** Includes media queries (e.g., `@media (max-width: 1100px)`) to adjust the Advanced Search layout for smaller screens.
* **Components:** Styles for the rounded search bar (`border-radius: 24px`), buttons (`.little-box`), and navigation links.

## 🚀 How to Run
1.  Download or clone the repository.
2.  Open `index.html` in any modern web browser.
3.  Type a query into the search bar and press Enter or click "Google Search" to see real results from Google.

## 🛠️ Technologies Used
* **HTML5**
* **CSS3** (Flexbox, Grid, Media Queries)
