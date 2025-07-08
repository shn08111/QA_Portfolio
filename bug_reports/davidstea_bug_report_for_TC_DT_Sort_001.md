# Bug Report – Products Not Sorted Alphabetically, A-Z

**Title:** Sorting products alphabetically in ascending order doesn’t sort all products  
**Reported By:** Sohjeong Yun  
**Date:** 07-04-2025  
**Severity:** Low  
**Environment:**
- Device: Laptop
- OS: Windows 11
- Browser: Chrome v137

---

## Steps to Reproduce

1. Go to https://davidstea.com/collections/loose-leaf-tea
2. Click on the "Sort by: Featured" dropdown list
3. Click on "Alphabetically, A-Z"

---

## Expected Result
- The page should show loose leaf tea products in alphabetically ascending order

## Actual Result
- Some products were in alphabetically ascending order, but some were not
- On page 2, "New York New York Tea" is followed by "Anji Green Tea"

---

## Screenshot
*A screenshot of loose leaf tea products that are not sorted in alphabetically ascending order:*
![Not sorted in alphabetically ascending order](../images/davidstea/alphabetically_ascending_error.png)

---

## Suggested Fix
- Add all products to the database with their correct names
- Review the code and fix any logic error on the alphabetically-ascending sorting algorithm


