# Day 11: Structured Output (JSON & Tables)

### **Objective**
To master the art of "Output Control"—forcing the AI to provide data in a specific structure that can be used in spreadsheets, databases, or web applications.

### **Why Structure Matters**
In a standard chat, AI uses "prose" (paragraphs). But for professional workflows, prose is hard to manage. **JSON (JavaScript Object Notation)** is the language of the internet. If you can get an AI to speak in JSON, you can feed that data directly into other apps.

### **The "Golden Rule" of Structure**
Never just say "Give me a list." Always say:
* "Format the output as a Markdown table."
* "Provide the response strictly in JSON format using these keys: [Item, Quantity, Cost]."

### **The Workflow Example**
* **Input:** A messy list of tools needed for a construction project.
* **Prompt:** "Analyze this list and output a JSON object categorized by 'Lumber', 'Hardware', and 'Tools'."
* **Result:** A clean, machine-readable block of data.

### **Implementation Task**
1. Take a messy paragraph of information (like a list of groceries or items in a room).
2. Ask the AI: "Extract all items from the text below and format them into a JSON array. Ensure each object has a 'name' and a 'category' key."
3. Observe how much easier it is to read than a standard list.

---
*Part of the AI Handshake 31-Day Curriculum.*
