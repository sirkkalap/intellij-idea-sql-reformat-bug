# intellij-idea-sql-reformat-bug

Open the SQL file
Edit line 5
Run Reformat Code with options (...)
  Set option "Only changes uncommitted to VCS"
  
Expected:
Lines 1 and 2 remain unchanged

Actual:
Lines 1 and 2 change too.
