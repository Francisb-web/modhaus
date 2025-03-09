npx create-react-app modhaus
cd modhaus
npm install react-router-dom lucide-react
npm start

echo "# ModHaus Interiors" >> README.md
echo "## Description" >> README.md
echo "A modern and elegant interior design website with portfolio, blog, e-commerce, and booking system." >> README.md
echo "## Installation" >> README.md
echo "1. Clone the repository: git clone https://github.com/YOUR_USERNAME/modhaus.git" >> README.md
echo "2. Navigate to the project folder: cd modhaus" >> README.md
echo "3. Install dependencies: npm install" >> README.md
echo "4. Start the development server: npm start" >> README.md

git add README.md
git commit -m "Added README file"
git push origin main
