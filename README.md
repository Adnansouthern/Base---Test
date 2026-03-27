for i in {1..100}
do
  echo "Commit $i" >> commits.txt
  git add .
  git commit -m "Commit 9"
