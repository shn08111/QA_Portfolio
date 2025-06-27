# Bug Report – Spotify Search Returns Results For Non-Existing Song Names

**Title:** Search returned results for a song name that does not exist  
**Reported By:** Sohjeong Yun  
**Date:** 06-25-2025  
**Severity:** Low  
**Environment:**
- Device: Desktop
- OS: Windows 10
- Browser: Chrome v137

---

## Steps to Reproduce

1. Go to https://open.spotify.com/search
2. Click on the search bar at the top of the page
3. Enter random letters such as "ejgheurtbkdf"

---

## Expected Result

- Search should return no results and display a “No results found” message  

## Actual Result

- Search returned results even though a song called "ejgheurtbkdf" does not exist
- The search result seemed to be irrelevant to the search input "ejgheurtbkdf"
- Interestingly, the search input "ejgheurtb" returned no results and displayed the following message: ‘No results found for "ejgheurtb"’

---

## Screenshot

*A screenshot of the search result for “ejgheurtbkdf”:*
![Search Result For “ejgheurtbkdf”](../../images/spotify/returns_result_for_ejgheurtbkdf.png)

*A screenshot of the search result for “ejgheurtb”:*
![Search Result For “ejgheurtb”](../../images/spotify/no_result_for_ejgheurtb.png)

---

## Suggested Fix

- Find out why different combinations of random letters lead to inconsistent search results and ensure consistent behavior

