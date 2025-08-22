# Frappe ERPNext Snippets

A VS Code extension with handy snippets for faster development in Frappe Framework and ERPNext. Quickly insert common patterns, API calls, hooks, and more.

## Features

### 🟢 Runtime Status
- This extension is lightweight with **no background processes**.
- It only provides snippets, so it has **zero impact on performance**.

### ⚡ Activation Events
- Snippets are automatically available when editing files in:
  - **ERPNext**
  - **Frappe**
  - **Jinja**
  - **Bench**

### ⌨️ Commands
- No custom commands.
- All functionality is provided via **snippets**.


## 🎥 Demo
![Frappe ERPNext Snippets Demo](assets/video.gif)

---


📦 **Installation**

**From VS Code:**  
1. Open Extensions (`Ctrl+Shift+X` / `Cmd+Shift+X`).  
2. Search for **Frappe ERPNext Snippets**.  
3. Click **Install**.

**From Command Line:**

```bash
code --install-extension ehsanjavaid.frappe-erpnext-snippets
```

🚀 **Usage**

Open `.py`, `.js`, or `.html/.jinja` files and start typing snippet prefixes like `frappe.get_doc` or `frappe.call`. Press Tab or Enter to insert.

🛠 **Development**

1. Clone repo:  
   ```bash
   git clone https://github.com/ehsanjavaid/frappe-erpnext-snippets.git
   ```
2. Edit `snippets/frappe.json` to add/update snippets.  
3. Build `.vsix` file:  
   ```bash
   vsce package
   ```

🤝 **Contributing**

PRs welcome! Fork, branch, and submit a pull request.

📬 **Author**

Developed by Ahsan Javaid. Open issues for questions or suggestions.
