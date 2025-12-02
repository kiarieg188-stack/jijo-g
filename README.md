# jijo-g
for motorcycle and mechanis worldwide
main
jijo-app/
├── src/
│   ├── components/
│   │   └── Header.js
│   ├── screens/
│   │   └── Dashboard.js
│   ├── services/
│   │   └── api.js
│   └── App.js
├── assets/
│   ├── logo.png
│   └── placeholder.png
├── README.md
├── package.json
└── .gitignore
{
  "name": "jijo-app",
  "version": "1.0.0",
  "description": "Mobile app for motorcycle riders and mechanics",
  "main": "src/App.js",
  "scripts": {
    "start": "node src/App.js"
  },
  "author": "George Kiarie",
  "license": "MIT"
}
node_modules/
.env
console.log("Welcome to Jijo App!");
export const Header = () => {
    console.log("Jijo App Header Component");
};
export const Dashboard = () => {
    console.log("Dashboard screen for riders and mechanics");
};
export const fetchData = () => {
    console.log("API service placeholder");
};
