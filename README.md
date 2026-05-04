# 📖 Flashcard Study

a simple and friendly tool to help you learn with flashcards.  
click on a card, check the answer, and track your progress.

---

## 🧠 what does it do?

- you upload a **csv file** with questions and answers  
- the app shows you one question at a time  
- you click the card to see the answer  
- then you tell if you got it **right** or **wrong**  
- your score stays on screen so you see how you are doing  

---

## 🚀 how to use it

### 1. prepare your csv file  
open a spreadsheet program (like excel or google sheets)  
make two columns:  
- first column = your question  
- second column = the answer  

save the file as `.csv` (comma separated values)

> example:

| question | answer |
| --- | --- |
| what is the capital of france? | paris |
| 2 + 2 = ? | 4 |

### 2. open the app  
open the html file in any modern browser (chrome, firefox, edge, safari)  
no internet needed after you open it

### 3. upload your file  
click "choose csv file" and pick your file  
the app will load your cards

### 4. study  
- read the question  
- click anywhere on the card to see the answer  
- click "got it right" or "got it wrong"  
- use **previous** and **next** to move between cards  

### 5. track your score  
on the top bar you will see:  
- progress (example: card 3 of 10)  
- correct answers ✅  
- incorrect answers ❌  

click **restart exam** to reset your score and start over

---

## ✨ special features

- **italic text** – write `$something$` in your csv and it will appear *italic*  
- **arabic language** – click "ar" in the top corner to switch to arabic  
- **works offline** – once the page is open, you do not need the internet  
- **responsive design** – works on phones, tablets, and computers  

---

## 📂 csv format rules

- the file must have at least two columns  
- first column = question, second column = answer  
- you can use quotes `"` around text if needed  
- empty rows are ignored  
- the app understands both `,` and line breaks normally  

---

## ❗ common problems

**"no valid flashcards found"**  
- check that your csv has two columns  
- make sure both columns have text (not empty)  
- save again as csv (not xlsx)

**"please upload a csv file"**  
- your file must end with `.csv`  
- open your excel file and choose "save as" → csv

**the card does not show the answer**  
- click on the white card area  
- wait a moment, the answer appears below the question

---

## 🛠️ for advanced users (optional)

if you want to change colors or text, open the html file in a text editor.  
you will find variables at the top inside `:root { ... }`  
example: change `--sage` to another color to change the green buttons.

---

## 🙌 why i made this

i wanted a simple flashcard tool that works without login, without installation, and without stress.  
just you, your cards, and a clean way to learn.  
i hope it helps you study better.

---

## 📄 license

free to use, share, and change for personal or school projects.

---

## 💬 feedback

if something is confusing or does not work, you can change the code yourself — it is all inside the html file.  
happy studying! 🎓
