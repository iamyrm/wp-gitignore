# WordPress wp-content .gitignore

A properly configured `.gitignore` file for the WordPress `wp-content` directory.

---

## 📦 What This Does

This `.gitignore` ensures that only your **custom themes, plugins, and mu-plugins** are tracked in version control, while excluding everything else inside `wp-content/` — including default WordPress files that shouldn't be committed.

---

## 📁 File Location

Place the `.gitignore` file in your WordPress `wp-content` folder:

---

## 🔧 The `.gitignore` Rules

```
# Ignore everything inside wp-content by default
/*

# But track these essential files and folders
!.gitignore
!/mu-plugins/
!/plugins/
!/themes/

# Exclude default WordPress plugins (not custom code)
/plugins/akismet
/plugins/hello.php

# Exclude default WordPress themes (not custom code)
/themes/twentytwentytwo
/themes/twentytwentythree
/themes/twentytwentyfour
/themes/twentytwentyfive
```
