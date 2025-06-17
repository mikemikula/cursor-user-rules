**1. PACKAGE MANAGEMENT**  
- Use `pnpm` only (never `npm`)  
- Run `pnpm verify` after every implementation  
- Use `@/` alias imports throughout  
- Ensure all workspace deps are installed  
- Scripts must respect `.gitignore`  
- VERY IMPORTANT REMOVE unused imports/vars 

---

**2. ERROR HANDLING**  
- Follow best-practice error handling  
- Capture all frontend console errors to server logs  
- Ensure errors are clear and actionable

---

**3. FORBIDDEN COMMANDS**  
NEVER run:  
- `rm -rf` (unless with exact path)  
- `pkill -f node`  
- `docker rm -f $(docker ps -aq)`
- pnpm dev

---

**4. UI/UX DESIGN**  
- Follow modern responsive best practices  
- Ensure cross-browser/device support  
- No inline styles or `!important`  
- Fix CSS with selector hierarchy, not force  
- ADD BEM for component classes

---

**5. CODE DOCUMENTATION**  
- Comment code purpose and logic clearly  
- Document key logic for maintainability

---

**6. GENERAL BEST PRACTICES**  
- Every var/method must be used  
- Follow SOLID, DRY, SoC  
- Fix errors before warnings  
- Use fail-fast debugging  
- No unused vars  
- Run `pnpm verify` after all changes  
- Implement `/` route correctly

---

**7. IMPORT RULES**  
- VERY IMPORTANT USE index files: `./` relative imports  
- Between components: use `@/` imports  
- Escape unescaped `"`, `'` per `react/no-unescaped-entities`

---

**8. TYPESCRIPT RULES**  
- Define interfaces for all API responses  
- Use type guards on unknown data  
- Replace all `any` with specific types  
- Add explicit return types to all functions  
- Fix `useCallback` deps as needed
