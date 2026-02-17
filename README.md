# ACLED MENA - Excessive Force Against Protesters

Interactive visualization mapping ACLED's MENA dataset of excessive force incidents against protesters from 2016 to present.

## 🌐 View Live Site

Visit the interactive map: [**[https://YOUR_USERNAME.github.io/ACLED_MENA_EVAP_Mapping/](https://YOUR_USERNAME.github.io/ACLED_MENA_EVAP_Mapping/)**](https://ccb2195-ux.github.io/ACLED_MENA_EVAP_Mapping/)

*(Replace YOUR_USERNAME with your GitHub username)*

## MY GOALS ->
- I wanted to get comfortable both analyzing and mapping ACLED data as I'm sure it will be coming up a lot for me. While I feel like I got a lot better at understand the ACLED data, I don't feel confident yet in my story telling ability across mediums (from Analysis -> dev -> writing -> publishing).

- I went in blind just hoping to find something shocking, and shocking it was. The excessive violence against protesters sub-category of data showed a huge spike in late 2025 corresponding directly with the start of the Iran protests in 2025, which I was able to confirm with the geolocation data.

- I didn't however touch on the most interesting finding yet, which is that the ACLED data shows a steady and unrelenting growth in peaceful protest movements across MENA which I will be diving into next.

- My analysis was mostly accomplished with facet wrapping in ggplot, though I think the area where I tried and failed the hardest was the design and execution of my interactive mapping feature. I wanted to have a sliding bar and a density measurement allowing the user to manually control the displayed data, and I wanted each point to contain relevant data for researchers to use, though I feel like I got only the bare minimum accomplished.

- I did all the analysis myself in R & python, and I employed Claude Code to help me quickly build the site. All of the Text on the site is written by me, but Claude helped my transition my ggplot from Rstudio into an Altair graphic since I can't seem to get the %%R magic box working in my python instance. 

## 📊 Features

- **Interactive Map**: Explore geographic distribution with timeline slider
- **Temporal Analysis**: Density plot showing event frequency over time
- **Mobile Responsive**: Optimized for desktop, tablet, and mobile viewing
- **Data-Driven**: Built with ACLED (Armed Conflict Location & Event Data Project) data

## 🛠️ Built With

- **Python**: Data processing and analysis
- **Folium**: Interactive mapping with Leaflet.js
- **Altair**: Statistical visualizations
- **Pandas**: Data manipulation
- **GitHub Pages**: Static site hosting

## 📁 Project Structure

```
├── index.html                  # Main website
├── ACLED_MENA_Map2.html       # Interactive Folium map
├── density_plot.png           # Timeline visualization
├── protest_map_MENA.ipynb    # Jupyter notebook with analysis
├── ACLED_MENA_Data.xlsx      # Source data
└── SETUP_GITHUB_PAGES.md     # Deployment guide
```

## 🚀 Setup & Deployment

See [SETUP_GITHUB_PAGES.md](SETUP_GITHUB_PAGES.md) for detailed instructions on deploying to GitHub Pages.

## 📖 Data Source

Data provided by the [Armed Conflict Location & Event Data Project (ACLED)](https://acleddata.com/), which collects real-time data on political violence and protest events worldwide.

## 📄 License

Data: ACLED (check ACLED's terms of use for data licensing)
Code: MIT License
