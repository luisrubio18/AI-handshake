# Day 4: Context Architecture & Guardrails

### **Objective**
To "Anchor" the AI using specific datasets (Static vs. Dynamic) and implement Guardrails to prevent hallucinations. This ensures the AI only speaks from the facts provided.

### **The Architecture**
1. **The Anchor (Static Data):** Hard facts that don't change (e.g., Torque specs for a Takeuchi TL8R2).
2. **The Sail (Dynamic Data):** Information that updates (e.g., Today's detailing schedule in Albuquerque).

### **The Guardrail Prompt**
"Use the provided context ONLY to answer the following question. If the answer is not contained within the text, state: 'I do not have sufficient data to answer this.' Do not attempt to guess or use outside knowledge."

### **Why it Works**
By separating your "Knowledge Base" from the "Instruction," you create a professional-grade AI tool. This is the difference between a chatbot that lies and an AI Assistant that operates with 100% accuracy.

---
*Part of the AI Handshake 31-Day Curriculum.*
