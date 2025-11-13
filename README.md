# XC Heatmap
A map of my 2025 Cross Country running data, as a heatmap! My  high school senior year was the first with a GPS watch, and I'm quite suprised this isn't a feature Garmin offers yet (that's why I made this).

Built using Leaflet.js, HeatLayer.js, their dependencies, and normal HTML.
# Data Source
This is a fun story...

I pull the `.fit` files off my Garmin watch via USB cable, and found a website that bulk converted them into a giant CSV table (Not sure how they were compressed... .zip rename didn't work).

I then (ab)used regex and Advent of Code-style skills to work the data into a giant array of `[x, y]` coordinate pairs.
# Ackknowledgements
A big thanks to the fine folks at OpenStreetMaps, and carto.com for making the maps, as well as the people behind Leaflet.js, HeatLayer.js, and simpleheat.js. And githack.com. Put simply, this project is mainly their tech glued together- I only processed the data.