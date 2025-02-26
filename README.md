# Mardi Gras Route Maps

**Work in progress**

## Description

This project downloads publicly available data and creates up-to-date MAPS of New Orleans Parade routes for Mardi Gras 2025.

![Chewbacchus Map](https://raw.githubusercontent.com/GarysCorner/MardiGrasMaps/refs/heads/master/RouteMaps/Chewbacchus.svg)

## Purpose

The purpose of this project is mostly to shore up my skills with GeoPandas and Geoplot.  However I did notice that when the City changes parade routes or schedules on short notice they do tend to publish the information very quickly on their [Data Portal](https://datadriven.nola.gov/home/).  I suspect this is because they use the routes to coordinate all kinds of related activity accross the city but who knows maybe the guy that does that just likes his job.  Regardless I saw an opportunity to make a process to regenerate static maps on the fly to account for changes.

While I realize I could achieve a more useful effect leverageing something like [LeafletJS](https://leafletjs.com/) or perhaps the GoogleMaps API for this kind of project, these arent the tools I tend to use in the real world.  Since I tend to use Matplotlib and Geoplot for spatial data since I'm trying to tell a story or show something spefici rather then make "dive your own data" sort of visualizations I wanted to get better with this project.

Inspiration for this kind of mapping and quick updates came from years of looking at [MardiGrasNewOrleans.com](https://www.mardigrasneworleans.com/parades/) which use to be static images.  I always liked the static images because I could download then on my cell and access them when the signal inevitably goes to sh*t during parades!

## Status

This project is working but needs some polish.  The maps need to look better the labeling needs better rotations (probably UTM conversion required), and I need to add in patches for other datasets.   Hopefully Ill get around to it, but you know how it is once a project is 75% complete, it stops being fun and I tend to put them down.  But whatever I dont put enough on github so here it is.

### Limitations and Usage

This code is provided as is to be used however.  The author (me) takes no responsibility for accuracy or how the code is use.  The code is for educational purposes only...namely to educate me so seriously whatever you do with it is on you!