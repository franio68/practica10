history | grep git
8 git init
9 git add .gitignore
10 git status
11 git add package.json
12 git status
13 git commit -m "chore: Estado inicial del proyecto: Se añade .gitignore y package.json"
14 git log
16 git add componentes/
17 git status
18 git commit -m "feat: Se añade directorio de componentes"
19 git log
20 git log --oneline
21 git log --oneline
22 git mv componentes components
23 git status
24 git commit -m "refactor: Renombrar componentes a components"
25 git log --oneline
26 git add componentes/
27 git add components/
28 git status
29 git commit -m "feat: Se implementan componentes Carrito y Producto"
30 git log --oneline
31 git log --oneline
32 git reset --soft a4dd78f
33 git status
34 git restore --staged
35 git restore --staged .
36 git status
37 git restore .
38 git status
39 git restore
40 git restore .
41 git status
42 git log --oneline
43 git status
44 git log --oneline
45 git show a4dd78f
46 git status
47 git history
49 git log --oneline
50 git reflog
51 git restore --source 753bb37 components/Carrito.jsx components/Producto.jsx
52 git restore --source 753bb37 components/Carrito.js components/Producto.js
53 git log --oneline
54 git status
55 git add components/
56 git commit -m "feat: Se recuperan componentes desde historial"
57 git log --oneline
58 git remote add origin https://github.com/franio68/practica10.git
59 git push -u origin main
60 git remote -v
61 git status
62 git add CHANGELOG.md
63 git commit -m "docs: Se añade CHANGELOG"
64 git status
65 git log --oneline
66 git push
67 git pull
68 git push
69 git log --oneline
70 git rm -r components/
71 git status
72 git commit -m "chore: Se elimina directorio components"
73 git status
74 git push
75 git remote -v
76 git log --oneline --all
77 git switch -c feature-components
78 git branch
82 git status
83 git add components/
84 git status
85 git commit -m"feat: Se desarrolla lógica de Carrito y Producto"
86 git log --oneline --all
87 git push origin feature-components
90 git status
91 git add components/
92 git status
93 git commit -m "feat: Se actualiza lógica de componentes"
94 git switch main
95 git add components/Producto.jsx
96 git status
97 git commit -m "feat: Se actualiza lógica de Productos"
98 git merge feature-components
99 git status
100 git add components/Producto.jsx
101 git status
102 git commit -m "feat: fusión de rama"
103 git log --oneline --all
104 git branch -d feature-components
105 git log --oneline --graph --all
106 git push
107 history | grep git
