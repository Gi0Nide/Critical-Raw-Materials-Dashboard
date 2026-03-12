# Κρίσιμες Πρώτες Ύλες — EU Dashboard 🇪🇺⚒️

Dashboard παρακολούθησης κρίσιμων ορυκτών πρώτων υλών, τιμών, εφοδιαστικής αλυσίδας και θέσης Ελλάδας.

**Website:** [oryktosploutos.net](https://www.oryktosploutos.net/)

---

## Γρήγορη Εκκίνηση

```bash
cd crm-dashboard-project
npm install
npm run dev
```

Ανοίγει στο `http://localhost:3000`

## Build & Deploy

```bash
# Build
npm run build

# Deploy στο Vercel
npm install -g vercel
vercel --prod

# Ή push σε GitHub → import στο vercel.com/new
```

## Ενσωμάτωση στο WordPress

```html
<iframe src="https://your-crm-dashboard.vercel.app"
        width="100%" height="800px"
        style="border:none; border-radius:8px;"
        title="CRM Dashboard">
</iframe>
```

## Δομή

```
crm-dashboard-project/
├── index.html
├── package.json            ← React 18 + Vite 6 + Recharts
├── vite.config.js
├── public/favicon.svg
├── src/
│   ├── main.jsx
│   ├── App.jsx
│   └── CRMDashboard.jsx   ← Το dashboard
└── README.md
```

## Τεχνολογίες

- React 18, Vite 6, Recharts

---

*oryktosploutos.net · Ελληνικός Ορυκτός Πλούτος · 2026*
