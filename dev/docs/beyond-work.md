---
title: Beyond Work
---

# Beyond Work

## 🌍 Travel & Places
<div id="map-container">
    <div id="worldmap" style="height: 400px; width: 100%; border-radius: 8px; margin: 20px 0;"></div>
</div>

<link rel="stylesheet" href="https://unpkg.com/leaflet@1.9.4/dist/leaflet.css" integrity="sha256-p4NxAoJBhIIN+hmNHrzRCf9tD/miZyoHS5obTRR9BMY=" crossorigin=""/>
<script src="https://unpkg.com/leaflet@1.9.4/dist/leaflet.js" integrity="sha256-20nQCchB9co0qIjJZRGuk2/Z9VM+kNiyxNV1lvTlZBo=" crossorigin=""></script>

<script>
document.addEventListener('DOMContentLoaded', function() {
    // Initialize the map
    var map = L.map('worldmap').setView([20, 0], 2);

    // Add the OpenStreetMap tiles
    L.tileLayer('https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png', {
        maxZoom: 19,
        attribution: '© OpenStreetMap contributors'
    }).addTo(map);

    // Define locations
    var locations = [
        { name: 'Seattle, WA', coords: [47.6062, -122.3321], type: 'home' },
        { name: 'Redmond, WA', coords: [47.6740, -122.1215], type: 'home' },
        { name: 'Bellevue, WA', coords: [47.6101, -122.2015], type: 'home' },
        { name: 'Amherst, MA', coords: [42.3732, -72.5199], type: 'home' },
        { name: 'Cambridge, MA', coords: [42.3736, -71.1097], type: 'home' },
        { name: 'Arlington, MA', coords: [42.4153, -71.1565], type: 'home' },
        { name: 'Belmont, MA', coords: [42.3956, -71.1776], type: 'home' },
        { name: 'Bangalore, India', coords: [12.9716, 77.5946], type: 'home' },
        { name: 'Portland, OR', coords: [45.5155, -122.6789], type: 'visited' },
        { name: 'Washington DC', coords: [38.9072, -77.0369], type: 'visited' },
        { name: 'Mount Rainier', coords: [46.8523, -121.7603], type: 'visited' },
        { name: 'Olympic National Park', coords: [47.8021, -123.6044], type: 'visited' }
    ];

    // Custom icons
    var homeIcon = L.divIcon({
        className: 'custom-marker home',
        html: '<span class="marker">🏠</span>',
        iconSize: [25, 25],
        iconAnchor: [12, 12]
    });

    var visitedIcon = L.divIcon({
        className: 'custom-marker visited',
        html: '<span class="marker">📍</span>',
        iconSize: [25, 25],
        iconAnchor: [12, 12]
    });

    // Add markers
    locations.forEach(function(loc) {
        var icon = loc.type === 'home' ? homeIcon : visitedIcon;
        L.marker(loc.coords, {icon: icon})
            .bindPopup(loc.name)
            .addTo(map);
    });
});
</script>

<style>
.custom-marker {
    text-align: center;
}
.marker {
    font-size: 20px;
    filter: drop-shadow(0 1px 3px rgba(0,0,0,0.3));
}
.leaflet-popup-content {
    font-size: 14px;
    padding: 4px;
    margin: 4px;
}
</style>

### Recent Adventures
- Hiking in Mount Rainier National Park
- 🚛 MBA Trek to Daimler Trucking, 🏗️ Autodesk, 🍵 Smith Tea, 🥤 PepsiCo in Portland, Oregon
- Beach camping in Olympic National Park
- Caribbean Cruise 🚢

## 🎨 Creative Pursuits

### Ceramics
- Workshop on wheel throwing at Eastside Pottery
- Favorite pieces: Handbuilding marine coral forms 
- Experimenting with different glazing techniques
- Created a series of wonky bowls 

### Weaving
- Learning weaving techniques on YouTube
- Creating modern wall hangings with natural fibers
- Exploring sustainable textile practices
- Recent project: Hand-woven wall art

### Digital Art
- Creating AI-assisted artwork
- Experimenting with generative art
- Blending traditional art with technology

## 🌱 Sustainability & Community
- Active member of local tech meetups and women in tech/product communities
- Advocate for sustainable technology practices

## 🎯 Personal Development
- Pilates and Strength Training. 

## 📚 Current Reading List
- "The Lean Product Playbook" by Dan Olsen
- "Thinking in Systems" by Donella H. Meadows
- "The Manager's Path" by Camille Fournier
- "Atomic Habits" by James Clear 