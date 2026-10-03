Q1. What did pwd print?
Answer: /Users/Ananya
Q2. What did ls -a show that plain ls did not?
Answer: It displayed all the hidden files/folders like .bash_history,.zsh_history,etc.
Q3. Pick one line from ls -l. What do you think the first column means?
Answer: drwx------@   4 Ananya  staff   128 14 Aug 16:11 Applications
This line shows the permission from owner, the name of the owner, the size of the directory, the size and the date it was last modified and name of folder.
Q4. Why does ls coding-cafe/week02 work from where you are standing? Which kind of path is coding-cafe/week02? Absolute or Relative?
Answer: It is a Relative Path. It works becuase in ls coding-cafe/week02, It looks for coding-cafe folder from the current directory (Users/Ananya) and then goes into week02 inside it. 
Q5. mv did two different jobs above. What were they?
Answer: First, it moved it to week01 folder, second time it was used to rename the folder. 
Q6. How many folders are on your PATH? (They are separated by :)
Answer: /Users/Ananya/.local/bin:/Library/Frameworks/Python.framework/Versions/3.13/bin:/usr/local/bin:/System/Cryptexes/App/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin:/var/run/com.apple.security.cryptexd/codex.system/bootstrap/usr/local/bin:/var/run/com.apple.security.cryptexd/codex.system/bootstrap/usr/bin:/var/run/com.apple.security.cryptexd/codex.system/bootstrap/usr/appleinternal/bin:/pkg/env/global/bin
There are 12 folders on my path
Q7. Write down exactly where your python3 lives.
Answer: /Library/Frameworks/Python.framework/Versions/3.13/bin/python3
Q8. Compare your answer to 7 with the person next to you. Are they the same? If not, why might that be?
Answer: No, its different becuase python can be installed in different loactions on a computer. Hence the path is different.
Q9. What exactly did the shell say? Explain the error in your own words, using the word PATH.
Answer: shell said "zsh: command not found: pyton3". This is because "pyton3" is not listed as a folder in my PATH. If I typed it correctly as python 3 then I would have found it.
Q10 .venv did not appear with plain ls. Why not?
Answer: .venv did not appear wiht plain ls as it is a hidden folder. All hidden folders begin with a dot.
Q11. What changed about your prompt?
Answer: (.venv) Ananya@Ananyas-MacBook-Pro coding-cafe % 
The prompt shows (.venv) at the beginning. 
Q12. Compare this with what you wrote down for question 7. Is it the same path? If not, what does that tell you about what activate actually did to your PATH
Answer: No, the paths are different. activate changed my PATH so my computer's terminal prompt now begins with .venv and it looks inside .venv in python.
Q13. What is in the second list that was not in the first?
Answer: Earlier list had - Package Version
------- -------
pip     26.1.2
The second list has- Package            Version
------------------ ---------
certifi            2026.7.22
charset-normalizer 3.5.1
idna               3.19
pip                26.1.2
requests           2.34.2
urllib3            2.7.0
Q14. Where does python3 point now?
Answer: /Library/Frameworks/Python.framework/Versions/3.13/bin/python3
Q15. Find what ls -h does. Write it in your own words.
Answer: ls -h shows file sizes in KB, MB, or GB, instead of just bytes.
Q16. What is the difference between what Ctrl + C and Ctrl + D did?
Answer: Ctrl + C stops the program that is running and Ctrl + D exits the Python prompt so it does not take any more input.
