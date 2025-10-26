
# END TO END  Project AGENTIC AI CHATBOT
=======
Steps to created Virtual Enviorment in Bash:

source ~/anaconda3/etc/profile.d/conda.sh

python -m venv chatbot

. chatbot/Scripts/activate


# Git push  A- ADDED   M -MODIFIED
git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin (source ~/anaconda3/etc/profile.d/conda.sh
git push -u origin main


src folder created(Source folder)
__init__.py (# Reason for created init is that src folder should be considered as package if tommorrow if need to import this package and upload in pypy then it will be usefull )

# Under src another folder is created langgraphagenticai and same __init__ to consider as package
# Under langgraphagenticai different components folder created with __init__
Below are the details
1)graph
2)LLMS
3)nodes
4)state
5)tools
6)UI (under UI folder created streamlitui folder and two files .py named loadui.py and display_result.py and also created uiconfigfile.ini)

# main.py and app.py is created main.py is created inside langraphagenticai
and app.py outside and under src(Source folder)

# requirements.txt file created to store all the dependencies
XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX


# UICONFIGFILE.INI  we given UI CONSTANTS
In UIconfigfile.py we created config class
from loadui.py loading the side bars of UI page and same integrated in main.py and app.py and UI testing workd fine

xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx







