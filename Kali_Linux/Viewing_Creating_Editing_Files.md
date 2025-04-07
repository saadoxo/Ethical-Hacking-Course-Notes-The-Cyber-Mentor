# Linux Commands for Text File Handling

### `echo`
- **`echo`** is used to add content to a text file.
  - To overwrite the file: `echo 'hey' > text.file`
  - To append to the file without overwriting: `echo 'hey' >> text.file`

### `touch`
- **`touch`** is used to create a new file.
  - Syntax: `touch <filename>`

### `nano`
- **`nano`** is an internal Kali Linux text editor.
  - Syntax: `nano <textfile-name>`

### `cut`
- **`cut`** is used to extract sections from each line of a file.
  - Example: `cut -d " " -f 3` eliminates sections based on a delimiter (e.g., spaces or semicolons) and the `-f 3` specifies which field to extract.
 
    ![image](https://github.com/user-attachments/assets/56895840-18c1-4f74-a5c1-03bcab3620c4)

