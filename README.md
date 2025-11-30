# 📘 SQL Window Functions Masterclass

*A concise collection of clear SQL window function examples with short explanations and helpful hints.*

## 🔍 About This Repository

This project contains **one clean example for each SQL Window Function**, including:

* A simple, easy-to-understand query
* A short explanation
* A small hint for interviews
* Not lengthy — everything is crisp and to the point

Designed for:
✔ Students
✔ Job seekers
✔ SQL interview preparation
✔ Quick revision of window functions

---

## 🧱 What’s Included

Each function includes:

* **Query example**
* **When to use it**
* **Key points**
* **Hints**

Functions covered include:

* `ROW_NUMBER()`
* `RANK()`
* `DENSE_RANK()`
* `NTILE()`
* `LAG()`
* `LEAD()`
* `FIRST_VALUE()`
* `LAST_VALUE()`
* `NTH_VALUE()`
* `SUM() OVER`
* `AVG() OVER`
* `COUNT() OVER`
* Partitioning & ordering variations
  …and more.

---

## 🛠 Sample Format (Used Across All Functions)

### 🔹 Function: ROW_NUMBER()

**Query**

```sql
SELECT 
    emp_name,
    salary,
    ROW_NUMBER() OVER (ORDER BY salary DESC) AS row_num
FROM employee;
```

**Explanation**
Assigns a unique sequence number to each row based on the ordering.

**Hint**
Perfect for selecting **1st highest**, **top 3**, removing duplicates, etc.

---

## 🎯 Who Should Use This?

* Beginners wanting simple examples
* Intermediate learners wanting clean practice queries
* Anyone preparing for **SQL interviews**
* Developers looking for a quick reference

---

## 🚀 Why This Repo is Useful

✔ Short & crisp examples
✔ Easy to revise
✔ Interview-friendly
✔ One example per function
✔ Useful hints for real SQL challenges

---

## 🤝 Contributions

Feel free to add more examples or improve explanations.
Pull requests are welcome
✅ More examples to add
Just tell me!
