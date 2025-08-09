# Frappe ERPNext Snippets

A Visual Studio Code extension that provides handy code snippets for faster development with **Frappe Framework** and **ERPNext**.  
Boost your productivity by quickly inserting common patterns, API calls, hooks, and other frequently used code blocks in your Frappe/ERPNext apps.

---

## ✨ Features
- **Prebuilt Frappe Snippets** – Commands, DocTypes, API calls, and server scripts.
- **ERPNext Utilities** – Frequently used business logic patterns.
- **Custom Hooks Templates** – Quickly scaffold hooks.py entries.
- **Python, JavaScript, and Jinja Support** – Context-aware snippets for multiple languages used in ERPNext apps.

---

## 📦 Installation
You can install this extension from the [Visual Studio Marketplace](https://marketplace.visualstudio.com/).

**From VS Code:**
1. Open Extensions sidebar (`Ctrl+Shift+X` / `Cmd+Shift+X` on Mac).
2. Search for **Frappe ERPNext Snippets**.
3. Click **Install**.

**From Command Line:**
```bash
code --install-extension FrappeERPnextSnippets.frappe-erpnext-snippets
```bash
🚀 Usage
Open a .py, .js, or .html/jinja file in VS Code.

Start typing the snippet prefix (e.g., frappe.get_doc, frappe.call) to trigger IntelliSense.

Press Tab or Enter to insert the snippet.

Example:
```bash
python
Copy
Edit
```bash
frappe.get_doc({
    "doctype": "Sales Invoice",
    "customer": "Customer Name"
}).insert()
```bash
🛠 Development
If you want to modify or add new snippets:

Clone this repo:

```bash
Copy
Edit
git clone https://github.com/ehsanjavaid/frappe-erpnext-snippets.git
```bash
Open in VS Code.

Edit snippets/*.json to add/update snippets.

Run:

```bash
Copy
Edit
vsce package
to build the .vsix file.
```bash
🤝 Contributing
Pull requests are welcome!
If you’d like to improve or add new snippets:

Fork the repo

Create a new branch

Submit a PR

📬 Author
Developed by Ahsan Javaid
For questions or suggestions, feel free to open an issue.