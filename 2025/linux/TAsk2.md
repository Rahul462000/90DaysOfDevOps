# **2️⃣ File & Directory Permissions**

- **Task:**
  - Create `/devops_workspace` and a file `project_notes.txt`.
  - Set permissions:
    - **Owner can edit**, **group can read**, **others have no access**.
  - Use `ls -l` to verify permissions.

1. Creating a new workspace that is a directory(folder)

### - `mkdir devops_workspace`

## - enter into the directory

### `cd devops_workspace`

- creating a file in the directory
  ### `touch project_notes.txt`
  - setting the permissions for the file based on Owner group and others
    ### `chmod 640 project_notes.txt`
