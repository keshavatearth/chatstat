Last weekend, I exported my ChatGPT history and tried to visualize it. Turns out that 21% of all my chats are about coding. And, I edit every message I send to ChatGPT at least once on average.

![image](https://github.com/user-attachments/assets/8b372a9b-7b05-45da-9209-f43682243774)
some other basic stats about my chatgpt usage

Here’s how I did it:

* generated a script with Gemini to get the complete schema of conversations.json (from the export)

* added that schema to chat. Suggested a few analysis options and asked for more. "How many chats contain code?" was Gemini's suggestion.

* asked Gemini to create the script in Python first. Reason: I've gotten better at debugging Python. Ran it locally, and it worked perfectly.

* shared the text output with Gemini and asked it to rewrite the script in JS for Gemini’s Canvas. Gemini also had to figure out the best UI to represent this type of data.

It took roughly 20 minutes. This repo has the code from gemini canvas if you export your data, download the file canvas.html, open it in chrome. Now, you can run the same analysis by uploading conversations.json from the export. All the analysis happens in your browser, so none of your data is shared with anyone.
