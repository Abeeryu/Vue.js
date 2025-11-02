# Vue.js + Vite Project

## Beschrijving

Het project is gebouwd met Vue.js, een populair framework voor interactieve en herbruikbare UI-componenten, en maakt gebruik van Vite, een snelle build tool en development server die moderne webontwikkeling eenvoudig maakt. Het project biedt een lichte en moderne basis voor je website.

### Wanneer gebruik je Vue + Vite?

- Als je interactieve componenten wilt bouwen met Vue.

- Als je een snelle development server wilt met hot module replacement (HMR).

- Als je een moderne, lichtgewicht front-end wilt zonder zware configuraties.

- Als je Tailwind CSS of andere CSS frameworks wilt gebruiken voor styling.

## Installatie

### Eerste poging met Vue CLI:

- Ik begint mijn Node-versie met npm -v.

- Installeerde Vue CLI globaal: npm install -g @vue/cli.

- Maakte een project aan: vue create myproject.

- Ging naar de projectmap: cd myproject.

- Probeerde de dev-server te starten: npm run dev.

Probleem: Het CLI-project gebruikt npm run serve in plaats van npm run dev, wat niet overeenkomt met de workflow die ik gewend ben in Vite- of Next.js-projecten.

### Overschakelen naar Vite voor consistentie:

- Om dat te doen, maakte ik een nieuw project met Vite:

npm create vite@latest myproject

- Vite voegt automatisch een dev script toe in package.json, zodat npm run dev nu werkt zoals verwacht.

### Clone de repository:

git clone https://github.com/Abeeryu/Vue.js.git

### Ga naar de projectmap:

cd Vue.js/myproject

### Installeer dependencies:

npm install

### Start de development server:

npm run dev

De site is nu beschikbaar op http://localhost:5173

## Technologieën

Vue.js – Voor interactieve UI-componenten.

Vite – Moderne development server en bundler.

Tailwind CSS – Voor snelle en moderne styling.

## Structuur van het project

myproject/
├─ public/             – Statische bestanden zoals favicon en afbeeldingen
├─ src/
│  ├─ assets/          – CSS, afbeeldingen of andere statische resources
│  ├─ components/      – Herbruikbare Vue componenten
│  ├─ App.vue          – Hoofdcomponent
│  └─ main.js          – Entry point van de applicatie
├─ index.html           – Hoofdpagina die Vite gebruikt als entry
├─ package.json         – Dependencies en scripts

## Gebruik

- Voeg componenten toe in src/components/ als .vue bestanden.

- Pas de hoofdstructuur aan in App.vue.

- Styling kan via Tailwind CSS of eigen CSS-klassen.

## Live Demo

Dit kan met Netlifiy en Vercel. Ik heb zelf vercel gebruikt.
Hier is de link (https://vue-js-bzjn.vercel.app/)

## Bronnen

https://www.geeksforgeeks.org/javascript/vue-js-introduction-installation/

https://vueframework.com/guide/installation.html#vite
