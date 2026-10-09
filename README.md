# 1. Create the project folder and README
mkdir my-project && cd my-project

cat > README.md << 'EOF'
# <Project Name>

## Project Details
- **Project Name:** <Project Name>
- **Description:** <one-line description>
- **Author:** <your name>

## Getting Started
<how to run the project>
EOF

# 2. Initialize git and commit
git init
git add README.md
git commit -m "Add README with project name details"

# 3. Create a PUBLIC repo on github.com (New repository, Public), then:
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
