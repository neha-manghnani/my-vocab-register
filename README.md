# my-vocab-register
📖 Vocabulary Register
A simple, mobile-friendly web app to help you collect and organize new words as you read.

What is this?
Vocabulary Register is your personal digital word collection. Whenever you come across a new word or phrase while reading, you can look it up here, get its definition with examples, and save it to your personal register — organized alphabetically for easy browsing.

Features
Feature	Description
📖 Dictionary Lookup	Type any word and get definitions + usage examples
🗣️ Slang Lookup	Look up informal terms, internet slang, and colloquialisms
💾 Save Words	One tap to save a word to your personal register
🔤 Alphabetical Organization	Words sorted A–Z with letter-based filtering
📊 Stats Dashboard	Track total words, letters covered, and weekly additions
🗑️ Delete Words	Remove any word you no longer need
📱 Works on Mobile	Designed for phone screens — add to home screen for app-like experience
🌙 Dark Theme	Easy on the eyes for reading
How It Works
Looking Up Words
Open the app

Type a word in the search box

Tap 📖 Define for standard definitions or 🗣️ Slang for informal meanings

Read the definitions and examples

Tap 💾 Save to Register to keep it in your collection

Browsing Your Register
Tap the 📚 My Words tab

Browse all your saved words (sorted alphabetically)

Tap a letter to filter — only letters with saved words are highlighted

View stats at the top: total words, letters used, words added this week

Dictionary Sources
The app uses multiple free dictionary APIs to cover the widest range of vocabulary:

Source	Button	Best For
Free Dictionary API	📖 Define	Common and intermediate words
Wiktionary	📖 Define (fallback)	Advanced, academic, and rare words
Urban Dictionary	🗣️ Slang	Informal terms, internet slang, new expressions
When you tap Define, the app first checks the Free Dictionary. If the word isn't found there (common with advanced vocabulary), it automatically falls back to Wiktionary, which has much broader coverage.

Setup Instructions (iPhone)
Step 1: Host the App (one-time setup)
Create a free account at github.com

Create a new repository named vocab-register

Make sure Public is selected

Check "Add a README file"

In your repo, go to Add file → Create new file

Name the file: index.html

Paste the entire app code into the editor

Tap Commit changes

Go to Settings → Pages

Under Source, select Branch: main, Folder: / (root)

Tap Save

Wait 1–2 minutes

Your app is now live at:

text

Copy
https://YOUR-USERNAME.github.io/vocab-register/
Step 2: Add to Home Screen
Open the URL above in Safari (must be Safari, not Chrome)

Tap the Share button (📤 square with arrow, bottom center)

Scroll down → tap "Add to Home Screen"

Name it "Vocab Register"

Tap Add

You now have an app icon on your home screen! 🎉

Privacy & Data
Question	Answer
Where are my words stored?	On your device only, in your browser's local storage
Can others see my words?	No — your vocabulary is 100% private to your device
What if I share the link?	They get their own empty register — your words are untouched
Does it need internet?	Only for looking up new words. Browsing saved words works offline
Can I lose my words?	Only if you clear Safari's website data. Don't do that!
Tips
🔑 Always use Safari — your words are tied to the browser you use

🚫 Don't clear Safari data — this erases your saved words

📶 Internet needed only for new lookups, not for browsing saved words

🔗 Share freely — the link works for anyone; each person gets their own register

📚 Build a habit — look up 3–5 new words every reading session

Limitations
Words are stored per-device (your phone and laptop have separate lists)

No cloud sync between devices

No account system — it's intentionally simple and private

Some very obscure words may not be in any of the free dictionaries

Made With
HTML, CSS, JavaScript (single file, no frameworks)

Free Dictionary API

Wiktionary REST API

Urban Dictionary API

localStorage for data persistence

Happy reading! 📚


