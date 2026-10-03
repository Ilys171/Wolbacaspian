# WolbaCaspian

WolbaCaspian is a network of low-cost, solar-powered environmental monitoring stations for the Caspian lowlands of Azerbaijan (Lankaran, Astara, Masallı region). Each station logs air temperature, water temperature, humidity, rainfall and standing water every 15 minutes. The readings are turned into a transparent estimate of mosquito **breeding-habitat suitability**, so that ditches, containers and tyres can be drained, covered or removed where conditions are most favourable. It does not release mosquitoes or *Wolbachia*, diagnose disease or predict outbreaks. Developed by Jeyla [Surname], [School], [City].

**Live site:** [GitHub link]

## Repository structure

```
wolbacaspian/
├── index.html      # page markup + inline JS (nav, scroll reveal, model widget)
├── style.css       # all styles; palette as CSS variables in :root
├── README.md       # this file
└── (suggested, later)
    ├── docs/       # methods note, calibration logs, scope document (PDF)
    ├── firmware/   # ESP32 station firmware
    ├── data/       # monthly CSV files, one per station: LNK-01_2026-05.csv …
    └── model/      # suitability index and model notebooks
```

## Editing

Open `index.html` in any text editor. Placeholders to replace are marked in square brackets: `[Surname]`, `[School]`, `[City]`, `[email]`, `[GitHub link]`. On the page they are highlighted in yellow by the CSS class `ph`. After you replace the text you can keep the `<span class="ph">` (still highlighted) or remove the span.

## Licence

[Choose a licence, e.g. CC BY 4.0 for text and data, MIT for code.]
