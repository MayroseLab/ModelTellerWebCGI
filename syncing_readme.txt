rsync -avzr --exclude *__pycache__* /Users/Oren/Dropbox/Projects/modelteller/backend/* bioseq@powerweb1.tau.ac.il:/var/www/cgi-bin/modelteller/
rsync -avzr --exclude *__pycache__* /Users/Oren/Dropbox/Projects/modelteller/webpage/* bioseq@powerweb1.tau.ac.il:/var/www/html/modelteller/
rsync -avzr /Users/Oren/Dropbox/Projects/modelteller/backend/{MODELTELLER_CONSTANTS.py,html_editor.py} bioseq@powerweb1.tau.ac.il:/bioseq/modelteller/auxiliaries/

