# 3D Pinokio Dashboard Customization Guide

## Background Customization

### Change Gradient Colors
#scene-container {
background: linear-gradient(to bottom, #0f0c29, #302b63, #24243e);
}
text

### Add Custom Background Image
#scene-container {
background: url('path/to/image.jpg') center/cover;
/* With gradient overlay */
background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)),
url('path/to/image.jpg') center/cover;
}
text

## App Statistics Display

### Add Counter HTML
<div class="stats-overlay"> <div class="stat-card">Running Apps: <span id="running-count">0</span></div> <div class="stat-card">Total Apps: <span id="total-count">0</span></div> </div> ```
Style the Counters
text
.stats-overlay {
    position: fixed;
    top: 20px;
    right: 20px;
    background: rgba(0,0,0,0.7);
    padding: 15px;
    border-radius: 10px;
    z-index: 100;
}
.stat-card {
    color: white;
    margin: 5px 0;
}
Update Counter Function
text
function updateCounters() {
    const runningApps = document.querySelectorAll('.item.running').length;
    const totalApps = document.querySelectorAll('.item').length;
    document.getElementById('running-count').textContent = runningApps;
    document.getElementById('total-count').textContent = totalApps;
}
```