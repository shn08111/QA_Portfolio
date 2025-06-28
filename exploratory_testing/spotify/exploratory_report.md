# Exploratory Testing Report – Spotify Website

**Tester:** Sohjeong Yun  
**Date:** 06-25-2025  
**URL Tested:** https://open.spotify.com  
**Environment:**
- Device: Desktop
- OS: Windows 10
- Browser: Chrome v137

---

## Areas Explored

- Login flow
- Search functionality
- Navigation

---

## Positive Observations

- Login is simple and fast
- Search result updates dynamically and quickly
- Easy to access key features like Home, Search, and Library
- UI is clean and intuitive

---

## Issues or UX Concerns

- Inconsistent search result for different combinations of random letters (see bug report for [TC_SP_Search_005](../../bug_reports/spotify_bug_report_for_TC_SP_Search_005.md))
- Unexpected behavior occurs in the search bar for certain combinations of special characters (see bug report for [TC_SP_Search_006](../../bug_reports/spotify_bug_report_for_TC_SP_Search_006.md))
- The left arrow to move back the text cursor does not work on the search bar but works on the search bar that appears when pressing Ctrl K

---

## Improvement Suggestions

- Find out why different combinations of random letters lead to inconsistent search results and ensure consistent behavior
- Fix the search bar behavior for special characters so that they don’t turn into their corresponding URL encoded values under certain conditions
- Ensure consistent behavior between the two search bars (the search bar at the top of the website and the search bar that appears when pressing Ctrl K)

---

## Screenshots or Examples

*A screenshot of the search bar at the top of the page:*
![Spotify Search Bar 1](../../images/spotify/search_bar_1.png)

*A screenshot of the search bar that appears when pressing Ctrl K:*
![Spotify Search Bar 2](../../images/spotify/search_bar_2.png)


