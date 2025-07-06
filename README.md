# RPA Challenge – UiPath Automation Bot 🤖

This is a full automation project built with **UiPath Studio** to solve the popular [RPA Challenge](https://rpachallenge.com), which involves dynamically filling a web form using data from an Excel sheet.

---

## 🚀 What the Bot Does

- Opens the RPA Challenge website
- Downloads the Excel file provided
- Reads and loops through the data
- Dynamically fills the form fields, even when the positions change after each submission
- Submits each form entry correctly
- Skips the header row to avoid typing column names
- Sends the downloaded Excel file via email to a specified recipient
- Uses delay and visual confirmation to show completion

---

## 🧠 Key Features

- ✅ Dynamic field detection using Anchor Base and Selectors
- ✅ Skips header rows without coding via row index logic
- ✅ Uses both Modern and Classic UiPath activities
- ✅ Professional structure: Excel read, loop, conditional logic, form submit
- ✅ Email automation built-in (SMTP/Outlook)

---

## 📂 Project Structure

```bash
RPAChallengeBot/
├── Main.xaml               # Main UiPath workflow
├── project.json            # UiPath project config
├── Input/
│   └── challenge.xlsx      # Excel file from the challenge
├── Screenshots/            # Debug screenshots (optional)
├── README.md               # This file
