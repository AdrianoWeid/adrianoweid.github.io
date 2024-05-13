---
layout: page
title: CLI-Satellitetracker
description: Tracks satellites in a command-line interface 
img: assets/img/cli_satellitestracker_logo.jpg
importance: 1
category: fun
---
## [Try Out Here](https://github.com/AdrianoWeid/cli-satellites)

CLI-Satellitetracker is a command-line interface application designed for searching and retrieving information about satellites.

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/cli_satellite.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
</div>
<div class="caption">
    This is a video, showcasing the Satellite Tracker.
</div>

### Installation
```zsh
git clone https://github.com/AdrianoWeid/cli-satellites.git
cd cli-satellites
python -m venv venv
source venv/bin/activate
venv\Scripts\activate
pip install -r requirements.txt
echo "N2YO_API_KEY=APIKEY" > .env #your N2YO API key
```
### To-Do
- **Enhance Search Functionality:** Implement search options to allow users to find satellites based on different parameters like name, orbit type, mission, or launch date.
- **Improve Error Handling:** Develop better error handling mechanisms to provide clearer feedback to users when searches fail or invalid data is entered.


