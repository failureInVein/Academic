2️⃣ CMD খোলা (non-negotiable)
Win + R → cmd → Enter


Admin দরকার হলে:

Start → cmd → Run as Administrator

3️⃣ Navigation (সবচেয়ে গুরুত্বপূর্ণ)
Current directory দেখো
cd

Folder change
cd Desktop
cd Downloads
cd FolderName

এক ধাপ পিছনে
cd ..

Drive change
D:

4️⃣ Files & Folders control
Folder বানাও
mkdir test

Folder delete
rmdir test


(খালি না হলে)

rmdir /s test

File বানাও
copy con file.txt


Ctrl+Z → Enter = save

File দেখো
type file.txt

File delete
del file.txt

5️⃣ List (what’s inside?)
dir


Useful flags:

dir /w   // wide view
dir /p   // page by page

6️⃣ Program run করা
Same folder এ থাকলে
program.exe

Current folder explicitly
.\program.exe

7️⃣ Compile & Run (C / C++)
gcc main.c -o main
main

g++ main.cpp -o main
main


Shortcut:

gcc main.c -o main && main

8️⃣ CMD power symbols (critical)
Symbol	Meaning
&&	আগেরটা সফল হলে পরেরটা
`	`
>	overwrite file
>>	append file

Example:

dir > list.txt

9️⃣ Environment & system info
cls         // clear screen
exit        // close CMD
whoami
hostname
echo %PATH%

🔟 Help system (underrated)
help


Specific command:

dir /?
cd /?

1️⃣1️⃣ CMD shortcuts (muscle memory)
Shortcut	কাজ
↑ ↓	command history
Tab	auto-complete
Ctrl + C	stop program
Ctrl + L	clear (PowerShell)