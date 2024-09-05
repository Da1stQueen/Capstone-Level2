echo "# erica-h-7-26-24-multi-page-website" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Da1stQueen/erica-h-7-26-24-multi-page-website.git
curl -sS https://webi.sh/gh | sh
gh auth login
git config user.name "Da1stQueen"
git config user.email "da1stqueen@gmail.com"
git push -u origin main