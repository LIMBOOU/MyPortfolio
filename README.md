# Personīgā Portfolio Tīmekļa Vietne

Pilnībā atsaucīga, moderna un pielāgojama vienas lapas personīgā portfolio, izveidota ar HTML5, CSS3, Bootstrap un animēta ar AOS (Animate On Scroll).

## 🎯 Funkcijas

✅ **Pilnībā Atsaucīga** - Optimizēta darbvirsmai, planšetei un mobilajām ierīcēm
✅ **Moderns Dizains** - Tīrs, minimālistisks un vizuāli pievilcīgs
✅ **5+ Sekcijas** - Galvene, Par mani, Prasmes, Pieredze, Kājene
✅ **Pielāgoti Fonti** - Google Fonts integrācija (Playfair Display & Poppins)
✅ **Gludas Animācijas** - AOS bibliotēka ar ritināšanas animācijām
✅ **Viegla Pielāgošana** - CSS mainīgie krāsām un atstatumiem
✅ **Ikonu Atbalsts** - Bootstrap ikonas sociālo mediju saitēm
✅ **Tīrs Kods** - Labi strukturēts HTML un CSS

## 📁 Mapes Struktūra

```
portfolio/
├── index.html          # Galvenais HTML fails
├── style.css           # Pielāgots CSS fails
├── images/
│   ├── profile.jpg     # Profila attēls
│   └── project-1.jpg   # Projektu attēli
└── README.md           # Šis fails
```

## 🎨 Kā Pielāgot

### 1. **Mainīt Krāsas**
Atveriet `style.css` un modificējiet CSS mainīgos augšdaļā:

```css
:root {
    --primary-color: #6366f1;      /* Mainiet uz savu zīmola krāsu */
    --secondary-color: #ec4899;    /* Mainiet uz savu akcentu krāsu */
    --dark-color: #1f2937;         /* Mainiet tumšo krāsu */
    --light-color: #f9fafb;        /* Mainiet gaiši fonu */
    --text-color: #374151;         /* Mainiet teksta krāsu */
}
```

### 2. **Mainīt Fontus**
Modificējiet fonta ģimenes mainīgos `style.css`:

```css
--font-display: 'Playfair Display', serif;  /* Virsrakstu fonts */
--font-body: 'Poppins', sans-serif;         /* Pamatnes teksta fonts */
```

Lai izmantotu dažādus Google Fonts:
1. Apmeklējiet [Google Fonts](https://fonts.google.com)
2. Atlasiet savus fontus
3. Kopējiet `<link>` tagu un aizstājiet to `index.html`
4. Atjauniniet CSS mainīgo nosaukumus

### 3. **Mainīt Teksta Saturu**
Vienkārši rediģējiet tekstu `index.html`:

- **Navigācija**: Mainiet saites nosaukumus un hrefs
- **Varoņu Sekcija**: Atjauniniet virsrakstu, apakšvirsrakstu un aprakstu
- **Par Mani**: Rediģējiet savu personīgo aprakstu
- **Prasmes**: Pievienojiet/noņemiet prasmes kartītes un mainiet virsrakstus
- **Projekti**: Atjauniniet projektu kartītes ar savu darbu
- **Kājene**: Mainiet e-pasta un sociālo mediju saites

### 4. **Pievienot Savus Attēlus**
1. Aizstājiet `images/profile.jpg` ar savu profila attēlu
2. Aizstājiet `images/project-1.jpg` ar savu projektu attēliem
3. Pārliecinieties, ka failu nosaukumi atbilst `src` atribūtiem `index.html`

### 5. **Mainīt Sociālo Mediju Saites**
Kājenes daļā atjauniniet `href` atribūtus:

```html
<a href="https://github.com/yourprofile" class="social-icon">
    <i class="bi bi-github"></i>
</a>
```

### 6. **Mainīt Kontakta E-pastu**
Atjauniniet e-pastu "Strādāsim Kopā" pogas:

```html
<a href="mailto:your-email@example.com" class="btn btn-primary btn-lg">
    Sūtiet Man E-pastu
</a>
```

### 7. **Modificēt Atstatumus**
Mainiet atstatumus CSS mainīgajos:

```css
--spacing-sm: 0.5rem;
--spacing-md: 1rem;
--spacing-lg: 2rem;
--spacing-xl: 3rem;
--spacing-xxl: 4rem;
```

## 🔧 Izmantotās Tehnoloģijas

- **HTML5** - Semantisks marķējums
- **CSS3** - Pielāgots stils ar mainīgajiem
- **Bootstrap 5** - Atsaucīga režģa sistēma
- **Google Fonts** - Pielāgota tipografija
- **Bootstrap Icons** - Ikonu bibliotēka
- **AOS (Animate On Scroll)** - Ritināšanas animācijas
- **JavaScript** - Gludas ritināšanas

## 📱 Atsaucība

- **Darbvirsma** (1024px+): Pilns izkārtojums ar 4 prasmes kolonnām
- **Planšete** (768px-1023px): 2 kolonnu izkārtojums
- **Mobilā Ierīce** (zem 768px): 1 kolonnu izkārtojums ar sakrautiem elementiem

## 🚀 Ātrs Sākums

1. Lejupielādējiet visus failus
2. Saglabājiet mapes struktūru
3. Atveriet `index.html` tīmekļa pārlūkprogrammā
4. Pielāgojiet pēc nepieciešamības (skatiet iepriekš)
5. Izvietojiet uz sava mitināšanas pakalpojuma

## 📄 Licence

Brīvi izmantojama un modificējama personīgiem vai komerciāliem projektiem.

## 💡 Padomi

- Izmantojiet augstākās kvalitātes attēlus, lai iegūtu labākus rezultātus
- Saglabājiet tekstu kodolīgu un spēcīgu
- Testējiet mobilajās ierīcēs pirms publicēšanas
- Atjauniniet sociālo mediju saites uz jūsu reālajiem profiliem
- Apsveriet iespēju pievienot kontaktu formu (nepieciešama aizmugure)
- Pievienojiet vairāk projektu, kad tos pabeigšat

---

**Gatavs parādīt savu portfolio? Lai veicas pielāgošanā! 🎉**