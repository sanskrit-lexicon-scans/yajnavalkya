
# convert index.txt to index.js and move to app1/ folder

python make_js_index.py I index.txt index.js
cp index.js ../index.js  # move up to app1 directory

-------------------------------------------------
Preliminary file copying:
--- for index.txt
cp /c/xampp/htdocs/sanskrit-lexicon/PWG/pwgissues/issue98/yajn_index_v1_edit.txt /c/xampp/htdocs/sanskrit-lexicon-scans/yajnavalkya/app1/pywork/index.txt

--- for make_js_index.py
cp /c/xampp/htdocs/sanskrit-lexicon/PWG/pwgissues/issue98/make_js_index.py /c/xampp/htdocs/sanskrit-lexicon-scans/yajnavalkya/app1/pywork/make_js_index.py

