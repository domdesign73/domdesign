cd domdesign

# Initialize Git repository
git init

git add .

git commit -m "Initial commit"

# Rename default branch to main
git branch -M main

# Add GitHub remote repository
git remote add origin https://github.com/domdesign73/domdesign.git

# Push code to GitHub
git push -u origin main

# Create README.md file
echo "# DomDesign Portfolio

This is the personal portfolio of Dominic Daniel, a graphic designer based in Hemmingford, Quebec. It showcases projects in logo design, branding, and visual communication. 

### 🛠 Built With
- HTML
- CSS
- Visual Studio Code

### 📌 Live Site
Visit: https://domdesign73.github.io/domdesign/

### 📬 Contact
Email: hello@domdesign.ca

" > README.md

git add README.md
git commit -m "Add README.md"
git push
