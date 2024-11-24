# VIM notes

### Reuse Last Selection
- **Command**: `gv`  
  - **Description**: Re-select the most recent visual selection.  
  - **Example Use Case**: Quickly adjust or re-edit closing tags after a change.  

---

### Join Lines

- **Command**: `J`  
  - **Description**: Joins the current line with the next one, adding a space between them.  
  - **Example**:  
    ```plaintext
    Line 1  
    Line 2
    ```
    After pressing `J`:
    ```plaintext
    Line 1 Line 2
    ```

- **Command**: `gJ`  
  - **Description**: Joins the current line with the next one **without** adding a space.  
  - **Example**:  
    ```plaintext
    Line 1  
    Line 2
    ```
    After pressing `gJ`:
    ```plaintext
    Line 1Line 2
    ```
