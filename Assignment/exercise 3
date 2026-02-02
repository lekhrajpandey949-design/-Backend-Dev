git checkout -b branch1
echo "Hello from branch1" > file.txt
git add file.txt
git commit -m "Edit file in branch1"

git checkout main
git checkout -b branch2
echo "Hello from branch2" > file.txt
git add file.txt
git commit -m "Edit file in branch2"

git checkout main
git merge branch1

git merge branch2


# Open file.txt, resolve conflict, then:
git add file.txt
git commit -m "Resolve merge conflict"
