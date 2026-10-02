# Current System Date Extractor in C++ 📅🕒

A clean, modular C++ solution that interfaces with standard system time utilities (`<ctime>`) to extract and map the operating system's real-time calendar date into a custom structured data model (`stDate`).

---

## 🌟 Highlights
- **Direct System Clock Access:** Uses `time(0)` to read UNIX epoch timestamps.
- **Date Normalization:** Corrects C++ zero-based month representations (`tm_mon + 1`) and the Gregorian epoch offset (`tm_year + 1900`).
- **Encapsulated Struct Architecture:** Encapsulates extracted values cleanly into a portable `stDate` object for downstream algorithm consumption.

---

## 💻 Sample Output
```text
Today's Date is: 2/10/2026
