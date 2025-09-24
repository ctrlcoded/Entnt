# TalentFlow – A Mini Hiring Platform

A **front-end React application** simulating a hiring platform for HR teams.  
It enables managing **jobs, candidates, and assessments** with realistic API behavior using MirageJS/MSW and local persistence via IndexedDB.  

---

## 🚀 Features

### 📌 Jobs
- Create, edit, archive/unarchive jobs  
- Reorder via drag-and-drop (optimistic updates & rollback)  
- Pagination & filtering (title, status, tags)  
- Deep linking to `/jobs/:jobId`  

### 👤 Candidates
- Virtualized list of 1000+ seeded candidates  
- Search (name/email) & filter by stage  
- Candidate profile with timeline of status changes  
- Kanban board for stage transitions (drag-and-drop)  
- Notes with `@mentions` (local suggestions only)  

### 📝 Assessments
- Assessment builder per job (single-choice, multi-choice, text, numeric, file upload stub)  
- Live preview of fillable form  
- Validation rules & conditional questions  
- Persist builder state and responses locally  
