# EJS Template Engine Fundamentals 📄

This repository explores **Server-Side Rendering (SSR)** using Node.js, Express, and the **EJS (Embedded JavaScript)** template engine. It demonstrates how to render dynamic HTML pages and manage reusable UI components.

## 📂 Project Structure

The project follows the standard MVC (Model-View-Controller) view structure:

| File/Directory | Description |
|----------------|-------------|
| **`index.js`** | Main server file configuring Express to use EJS as the view engine. |
| **`views/`** | Contains all the template files (`.ejs`). |
| **`views/home.ejs`** | The main landing page template. |
| **`views/about.ejs`** | Example of a secondary page route. |
| **`views/components/`** | **Partials** folder for reusable code blocks (DRY principle). |
| **`.../header.ejs`** | A reusable navigation/header component included in multiple pages. |

## 🛠️ Features Demonstrated

* **Dynamic Content:** Passing data from the server (`index.js`) to the views.
* **Partials & Includes:** Using `<%- include('components/header') %>` to reuse the header across Home and About pages.
* **Logic in Views:** Using JavaScript logic (loops, conditionals) directly within HTML.

## 🚀 Getting Started

### Installation

1.  Clone the repository:
    ```bash
    git clone [https://github.com/YOUR-USERNAME/ejs-template-fundamentals.git](https://github.com/YOUR-USERNAME/ejs-template-fundamentals.git)
    ```

2.  Install dependencies (Express & EJS):
    ```bash
    npm install
    ```

### Usage

Start the server:

```bash
node index.js