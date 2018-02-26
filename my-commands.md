 1782  cd git-drill-1
 1783  git init
 1784  touch read.md index.html style.css
 1785  git remote add origin https://github.com/cchooley/git-drill-1.2.git
 1786  git add index.html
 1787  git status
 1788  git commit -m "Added index.html"
 1789  pico read.md
 1790  git add -A
 1791  git reset
 1792  touch app.js
 1793  git add -A
 1794  git commit -m "Adding caged and all remaining files"
 1795  git log
 1796  git push -u origin master
