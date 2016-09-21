---
title: How to log core data queries
tip-number: 03
tip-username: arasu01
tip-username-profile: https://github.com/arasu01
tip-description: logging core data queries in console.


---

Steps to log the core data queries in console

1. Select Edit Scheme from the scheme editor menu.
![Editor menu](Editor_menu.png "Editor menu")
2. Select the Test action and move to arguments section.
3. Add the follwing command in run arguments : 

```bash
-com.apple.CoreData.SQLDebug 1
```

![Edit scheme](Edit_scheme.png "Edit scheme")

4. Build and Run your project you will see the SQL queries in console.
![SQL queries](SQL_queries.png "SQL queries")
