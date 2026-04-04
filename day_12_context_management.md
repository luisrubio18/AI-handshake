# Day 12: Context Window Management

### **Objective**
To understand the "Memory Limit" of AI models and learn how to prune, summarize, and bridge context to maintain high-quality outputs over long sessions.

### **The Concept**
Every AI has a "Context Window"—a set amount of text it can "read" at one time. Once a conversation gets too long, the AI starts dropping the earliest parts of the chat to make room for new info. 

### **The "Memory Leak" Warning Signs**
* The AI starts repeating itself.
* It forgets specific constraints you set at the beginning (e.g., "Keep it under 100 words").
* It loses the "Persona" or tone you established.

### **Tactics for Mastery**
1. **The "Anchor" Prompt:** Every 10-15 prompts, give the AI a summary of the project so far and ask it to confirm.
2. **Context Pruning:** If a chat gets too "noisy," start a fresh chat and paste only the essential "Active" data.
3. **The "Clean Slate" Method:** When switching tasks within the same project, tell the AI: "Clear all previous creative constraints, but keep the technical data for [Project X]."

### **Implementation Task**
1. Review a long chat history. 
2. Identify the "Core Truths" (the most important rules/data).
3. Draft a "Context Bridge" prompt: "We are moving to the next phase of [Project]. Here is a summary of our progress: [Summary]. Do you have all the necessary data to proceed?"

---
*Part of the AI Handshake 31-Day Curriculum.*
