# Bug & Observation Report

## Bugs Identified

### 1. No Internet Handling
- Script crashes if internet is disconnected
- No user-friendly error message

---

### 2. Dependency on Website Structure
- If HTML structure changes, scraper will fail

---

### 3. No Input Validation
- Negative or invalid page numbers are not properly handled

---

### 4. Slow Execution
- Scraping multiple pages takes time

---

## Observations

- Data accuracy depends entirely on website structure  
- Selenium performance varies with system speed  
- No retry mechanism for failed requests  

---

## Recommendations/ Future Work

- Add exception handling for network errors  
- Validate input parameters  
- Implement logging system  
- Optimize scraping speed  
