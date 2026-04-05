# Test Cases - Book Scraper

---

## TC01: Launch Scraper

**Feature:** Program Execution  

**Steps:**
1. Run script using terminal  

**Expected Result:**  
Program should start without errors  

**Actual Result:**  
Program started successfully  

**Status:** Pass  

---

## TC02: Scrape Single Page

**Feature:** Data Extraction  

**Steps:**
1. Run with --pages 1  

**Expected Result:**  
Books from 1 page should be scraped  

**Actual Result:**  
Data extracted correctly  

**Status:** Pass  

---

## TC03: Scrape Multiple Pages

**Feature:** Pagination  

**Steps:**
1. Run with --pages 3  

**Expected Result:**  
Data from 3 pages should be collected  

**Actual Result:**  
Multiple pages scraped successfully  

**Status:** Pass  

---

## TC04: CSV File Creation

**Feature:** File Output  

**Steps:**
1. Run script  
2. Check output file  

**Expected Result:**  
CSV file should be created  

**Actual Result:**  
File created successfully  

**Status:** Pass  

---

## TC05: Data Accuracy

**Feature:** Data Validation  

**Steps:**
1. Compare scraped data with website  

**Expected Result:**  
Data should match website  

**Actual Result:**  
Data matched correctly  

**Status:** Pass  

---

## TC06: Invalid Page Input

**Feature:** Input Handling  

**Steps:**
1. Run with --pages 0  

**Expected Result:**  
System should handle gracefully  

**Actual Result:**  
No crash observed  

**Status:** Pass  

---

## TC07: Next Page Navigation

**Feature:** Navigation  

**Steps:**
1. Scrape multiple pages  

**Expected Result:**  
Next button should work  

**Actual Result:**  
Navigation successful  

**Status:** Pass  

---

## TC08: Internet Failure

**Feature:** Error Handling  

**Steps:**
1. Disconnect internet  
2. Run script  

**Expected Result:**  
Error should be handled  

**Actual Result:**  
Script failed without proper message  

**Status:** Fail  
