## 🛠️ Summary
Briefly explain what this pull request does.  
Example:  
Fixes incorrect import of `EmptyDataException` and replaces it with the proper reference from the `sealed class`.

---

## 📌 Description

### ✅ Changes made:
- Removed invalid import: `org.example.logic.EmptyDataException`
- Updated code to use: `FoodMoodException.Validation.EmptyDataException`
- Ensured exception handling follows sealed class structure.

---

## 🚀 Motivation
Why was this change necessary?  
Example:  
To fix a compilation error caused by incorrect import and to ensure proper exception reference in validation logic.

---

## 🔍 Testing
Please check what has been verified before merging:

- [x] Code compiles successfully
- [x] Unit tests (if any) pass
- [x] Feature behaves as expected
- [ ] Manually tested the affected logic

---

## 📎 Related Issues / Tasks
Link to any related issue or task:
- Resolves: `#issue_number` (if applicable)

---

## 👥 Reviewers
Optional: Tag team members you want to review the changes  
Example: `@teammate1` `@leadDev`
