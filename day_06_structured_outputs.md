# Day 6: Structured Outputs (JSON Formatting)

### **Objective**
To force the AI to return data in a consistent, machine-readable format (**JSON**) instead of conversational text. This is essential for data science and application development.

### **The JSON Structure**
Instead of a paragraph, we request a "Data Object":
```json
{
  "client_name": "[NAME]",
  "vehicle_type": "[VEHICLE]",
  "service_price": "[PRICE]",
  "scheduled_date": "[DATE]"
}
