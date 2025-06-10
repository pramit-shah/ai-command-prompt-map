# 🗂️ Project File Tree – Live Build Reference

> All files and folders must be logged here.  
> Every change (add, edit, delete) is tracked with a `CMT-ID` link to `build_comment_log.md`.

---

## 🌳 FILE TREE STRUCTURE

/project-root
│
├── /src
│ ├── index.js # CMT-001 (created)
│ ├── /api
│ │ ├── auth.js # CMT-002 (added JWT logic)
│ │ └── user.js # CMT-004 (added CRUD ops)
│ ├── /services
│ │ └── authService.js # CMT-006 (refactor logic)
│ ├── /models
│ │ └── userModel.js # CMT-003 (schema defined)
│
├── /config
│ └── db.js # CMT-005 (Mongo connection)
│
├── /logs
│ └── error.log # CMT-009 (log setup)
│
├── .env.example # CMT-007
├── README.md # CMT-010
├── build_comment_log.md # AUTO-MANAGED
├── file_tree.md # AUTO-MANAGED