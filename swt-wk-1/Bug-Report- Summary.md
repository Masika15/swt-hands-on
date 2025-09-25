# 🐞 Bug Report Summary

## 🧾 Student Details  
**Name**: Doreen Masika  
**Cohort**: July 2025  
**Date**: 9, September 2025

---

## ✅ Expected Behaviors  
List 3 things you expect the Weather Checker app to do correctly.

1. Accept city names in any case format - Whether I type "nairobi", "NAIROBI", or "Nairobi", the app should find and display the weather data correctly.
2. Provide clear feedback for invalid inputs - When I submit an empty field or invalid city name, the app should display a helpful error message explaining what went wrong.
3. Display weather information clearly - When a valid city is entered, the app should show the city name, temperature, and weather condition in a readable, properly formatted way.
---

## 🐛 Reported Bugs  

### 🐞 BUG-001  
**Title**: App doesn’t handle uppercase or mixed-case city names  
**GitHub Link**: [Paste Issue Link Here]  
**Requirement Affected**: Input Validation  
**Severity**: Medium  
**Summary**:  
The app only recognizes city names in exact lowercase format, rejecting valid cities typed in uppercase or proper case. This creates a poor user experience since users naturally capitalize city names like "London" or "New York".

---

### 🐞 BUG-002  
**Title**: App doesn’t handle city names with leading/trailing spaces  
**GitHub Link**:swt-wk-Issue #1  
**Requirement Affected**: UI Feedback  
**Severity**: Medium  
**Summary**:  
When users click "Check Weather" with an empty input field, the app provides no visual feedback or error message. Users are left confused about whether the app is working properly or what action they should take.

---

## 💭 Reflection  

Answer briefly (1–2 paragraphs):

- What was your testing approach? I used systematic boundary testing, starting with normal "happy path" scenarios (valid lowercase city names) before testing edge cases like uppercase input, empty fields, and special characters. I also tested user experience elements like keyboard navigation (Enter key) and visual feedback. This methodical approach helped me identify both functional bugs and usability issues.
- What did you find easy or difficult during the task? The testing process was straightforward once I understood the app's expected behavior. The most challenging part was determining appropriate severity levels for each bug - balancing technical impact with user experience implications. Writing clear, reproducible steps was easier than expected because the bugs were consistent and predictable.
- How confident are you now in identifying and reporting bugs? I feel much more confident in systematic bug testing and reporting. This exercise taught me to think from a user's perspective while also considering technical requirements. I now understand the importance of clear documentation and structured reporting formats. The practice of categorizing bugs by severity and affected requirements will be valuable for future testing assignments.
