# Bug Report – Products Not Sorted By Price, From Low To High

**Title:** Sorting products by price from low to high doesn’t sort all products  
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
3. Click on "Price, low to high"

---

## Expected Result
- The page should show loose leaf tea products from low price to high price

## Actual Result
- Most products were sorted by price, from low to high, but some products were not, especially on page 1
- For products that are on sale, the price before discount seems to be considered as the price when getting sorted

---

## Screenshot
*A screenshot of loose leaf tea products that are not sorted from low price to high price:*
![Not sorted from low price to high price](../images/davidstea/low_to_high_price_error.png)

---

## Suggested Fix
- Add all products to the database with their correct prices, taking the discounted prices in consideration
- Review the code and fix any logic error on the low-to-high-price sorting algorithm


