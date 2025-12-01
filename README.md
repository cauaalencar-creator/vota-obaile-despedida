votacao-baile/
│
├── public/
│ └── index.html
│
├── src/
│ ├── components/
│ │ ├── Header.jsx
│ │ ├── NomineeCard.jsx
│ │ ├── VotingSection.jsx
│ │ └── Results.jsx
│ │
│ ├── pages/
│ │ ├── Home.jsx
│ │ ├── Admin.jsx
│ │ └── Login.jsx
│ │
│ ├── hooks/
│ │ └── useVotes.js
│ │
│ ├── App.jsx
│ ├── main.jsx
│ └── index.css
│
├── .gitignore
├── package.json
├── tailwind.config.js
└── README.md
```


---


## 📝 `public/index.html`
```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Votação — Baile</title>
</head>
<body class="bg-gray-100">
<div id="root"></div>
<script type="module" src="/src/main.jsx"></script>
</body>
</html>
```
---
