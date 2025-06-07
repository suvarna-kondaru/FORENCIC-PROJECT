 Forensics Activity Logger
This is a Forensics Activity Logger developed using Python and Tkinter to extract and analyze user activity data from mobile devices. The application helps digital forensics experts or investigators process and filter logs/data collected from mobile sources (like browser history, messages, or app logs exported as HTML/text).

Features
Upload Mobile Data: Upload mobile-exported files (e.g., browser history in .html format).

 Extract Data: Parses and extracts the text from HTML content using BeautifulSoup.

Forensics Activity Analysis: Displays metadata such as file creation/modification time and file size.

Filter Activity Logs: Filters log lines containing timestamps (like AM/PM entries).

Exit: Cleanly exits the application.

Tech Stack
Python 3

Tkinter for GUI

BeautifulSoup for parsing HTML content

Standard Libraries: datetime, pathlib, filedialog, os

