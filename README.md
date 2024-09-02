<h1>Git Clone Assignment</h1>
<p>Getting the knowledge of cloning a git repository and pushing it to your own repository seemlessly</p>

![Screenshot (85)](https://github.com/user-attachments/assets/821f16e8-2704-4e42-8fb6-b2b503fc8749)

## Creating a folder where the repository will be cloned into,  with the following command

mkdir "folder name"
mkdie "Assignment5"

### Clone the respository into your local machine; git clone "URL~your reposiroty"

Remove the existed README.md file and replace with a new README.md file

rm -r README.md

touch README.md

### Edit the new README.md file to desired output

vim README.md

### Add the Folder to the stagging area and commit the file

git add .

git commit -m "MESSAGE"

git commit -m "Updating README.md file"

![Screenshot (87)](https://github.com/user-attachments/assets/4159bfc0-4e0e-4b6d-b161-4a5786a35d50)

## To push the repository into another (your) repository, you will need to rename the branch and add the address of your respository into the git commmand

git remote rename origin upstream
git remote add origin https://github.com/elijahfaith/GITHUB_Clone.git

### Then push the file into your own repository.
git push origin main

![Screenshot (88)](https://github.com/user-attachments/assets/47374f0a-9ce7-4a3a-ab02-f3fb41a3d1f5)

<h1>Thank you</h1>

Let's know if its helps, kindly give us some stars.



