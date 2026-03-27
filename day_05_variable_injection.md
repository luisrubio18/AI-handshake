# Day 5: Variable Injection & Template Scaling

### **Objective**
To create "Plug-and-Play" prompt templates using `[VARIABLES]`. This allows one high-performing prompt to be reused for hundreds of different scenarios without rewriting the core logic.

### **The Variable Framework**
Instead of writing a new prompt for every client, we use placeholders:
"Act as a professional marketing consultant. Write a 3-sentence outreach email for a client named **[CLIENT_NAME]** who owns a **[VEHICLE_TYPE]**. Focus on the benefit of **[SERVICE_TYPE]** for their specific location in **[LOCATION]**."

### **Why it Works**
Variable Injection is the "API Mindset." It prepares you to integrate AI into spreadsheets, websites, or apps. You define the **Logic** once, and let the **Data** change.

### **Implementation Task**
1. Define the System Role.
2. Identify the repeating data points.
3. Use brackets `[]` to mark where the data will be "injected."

---
*Part of the AI Handshake 31-Day Curriculum.*
