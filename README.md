VERY IMPORTANT - NEVER CREATE .MD FILES

VERY IMPORTANT USE DRY, SOLID, SOC BEST PRACTICE DESIGN PATTERNS

VERY IMPORTANT - WRITE CODE IN THE LEAST AMOUNT OF LINES, BUT MAKE SURE ITS READABLE

**1. PACKAGE MANAGEMENT**  
- Ensure all workspace deps are installed  
- Scripts must respect `.gitignore`  
- VERY IMPORTANT REMOVE unused imports/vars 

---

**2. ERROR HANDLING**  
- Follow best-practice error handling  
- Capture all frontend console errors to server logs  
- Ensure errors are clear and actionable

---

**4. UI/UX DESIGN**  
- Follow modern responsive best practices  
- Ensure cross-browser/device support  
- No inline styles or `!important`  
- Fix CSS with selector hierarchy, not force  
- Use BEM for component classes for component naming

---

**5. CODE DOCUMENTATION**  
- Comment code purpose and logic clearly  
- Document key logic for maintainability

---

**6. GENERAL BEST PRACTICES**  
- VERY IMPORTANT - WRITE CODE IN THE LEAST AMOUNT OF LINES, BUT MAKE SURE ITS READABLE
- Every var/method must be used  
- Follow SOLID, DRY, SoC  
- Fix errors before warnings  
- Use fail-fast debugging  
- No unused vars  
- Implement `/` route correctly

---

**8. TYPESCRIPT RULES**  
- Define interfaces for all API responses  
- Use type guards on unknown data  
- Replace all `any` with specific types  
- Add explicit return types to all functions  
- Fix `useCallback` deps as needed
