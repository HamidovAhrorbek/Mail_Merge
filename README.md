📬 Mail Merge Project

This project is part of my journey through the **100 Days of Code - Python Bootcamp** by Angela Yu on Udemy.


📝 Project Description

The **Mail Merge** tool automates the process of creating personalized letters for multiple recipients. It reads a list of names from a text file and inserts each name into a letter template. The personalized letters are then saved in a designated output folder.


🧠 What I Learned

📄 File handling in Python
✂️ String manipulation (`str.replace()`, `.strip()`)
📁 Directory and file path management


🗂️ Project Structure

📁 Mail-Merge-Project/
*  📂 Input/
 *  📂 Letters/
  *  📝 starting_letter.txt
 *  📂 Names/
  *  🧾 invited_names.txt
* 📂 Output/
 * 📂 ReadyToSend/
  * 📄 letter_for_<name>.docx
* 🐍 main.py


⚙️ How It Works


1. 📥 Reads names from `invited_names.txt`
2. 📤 Opens the letter template `starting_letter.txt`
3. 🔁 Replaces the placeholder `[name]` with each actual name
4. 💾 Saves the personalized letters to the `Output/ReadyToSend/` directory


 ✉️ Example

If `invited_names.txt` contains:

John
Jane
Tom

And `starting_letter.txt` contains:

Dear [name],

You are invited to my birthday his Saturday.

Hope you can make it!

Then it generates:
- `letter_for_John.docx`
- `letter_for_Jane.docx`
- `letter_for_Tom.docx`

Each file will contain:

Dear John,

You are invited to my birthday his Saturday.

Hope you can make it!


🚀 How to Run

1. 📦 Clone this repository  
2. 📂 Place your name list and letter template inside the appropriate folders in the `Input/` directory  
3. ▶️ Run `main.py`  
4. 📁 Check the `Output/ReadyToSend/` folder for your personalized letters 


🔮 Future Improvements

* 🧾 Add support for `.pdf` or styled `.docx` formats  
* 🖥️ Create a user-friendly GUI using Tkinter or PyQt  
* ⚠️ Add error handling for missing files or invalid formats

