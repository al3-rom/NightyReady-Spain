# NightReady BCN 🕺🌃

**NightReady BCN** is a personal project that helps people in Barcelona plan their night out.
It combines club listings with reviews and practical advice on how to dress, where to pre-drink, and how to get home safely.

This site is built with [Astro](https://astro.build/) and [TailwindCSS](https://tailwindcss.com/).

---

## 🚀 Features

- ✅ Club directory with images, music style, area, and age range
- ✅ Club detail pages (`/clubs/[slug]`)
- ✅ Outfit and preparation tips
- ✅ Transport info for safe return
- ✅ Component-based design (Astro)
- ✅ JSON-powered dynamic content

---

## 📁 Project Structure

```
src/
├── components/       → Reusable components (e.g., ClubCard)
├── data/             → Static data (JSON for clubs)
├── pages/
│   ├── index.astro           → Homepage
│   ├── clubs/index.astro     → Club list
│   ├── clubs/[slug].astro    → Club details
│   ├── prep/index.astro      → Tips for the night
│   ├── prep/outfits.astro    → What to wear
│   └── prep/transport.astro  → How to get home
public/
└── images/clubs/     → Images for each venue
```

---


## 📌 Goals

This project was made to:
- Practice Astro + TailwindCSS
- Learn to work with components and data
- Build a useful and fun web experience

