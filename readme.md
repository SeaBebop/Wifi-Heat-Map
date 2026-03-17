## WiFi Coverage Heatmap Survey

Quick manual site survey of my home network using a free WiFi analyzer app (walkaround method). Data is approximate/limited but highlights real attenuation issues from walls and placement.

### Setup
- Access Point: Verizon Router
- Bands tested: Primarily 5 GHz 
- Method: Walked the floor plan, recorded signal (dBm), speed (Mbps), ping (ms), interference at ~30–50 points
- Tool: Wifi Heatmap by Wi-Fi Solutions

### Key Findings
- Strong coverage in central living/kitchen area (close to AP): -45 to -65 dBm, 50–200+ Mbps
- Drops in kitchen & bathroom: Often -70 to -85 dBm, speed <50 Mbps, ping spikes >100 ms
- Main cause: Attenuation through 1–3 interior walls (not heavy neighbor interference) 
- Right bedroom & edges: Marginal (yellow zones), left bedrooms better due to fewer obstacles and distance

### Heatmaps
Here are the captured screenshots (click to enlarge):

**Signal Strength (dBm)**  
![image](https://github.com/SeaBebop/Wifi-Heat-Map/blob/main/Wifi%20Heatmap%203-17-2026/WiFi%20Heatmap%20Signal.jpg?raw=true)
*Red = strong (-45 dBm), blue = weak (-85 dBm), gray = no signal*

**Link Speed (Mbps)**  
![image](https://github.com/SeaBebop/Wifi-Heat-Map/blob/main/Wifi%20Heatmap%203-17-2026/WiFi%20Heatmap%20Speed.jpg?raw=true)
*Blue = fast (50–200+), red = slow (<50 or drops)*

**Ping Latency (ms)**  
![image](https://github.com/SeaBebop/Wifi-Heat-Map/blob/main/Wifi%20Heatmap%203-17-2026/WiFi%20Heatmap%20Ping.jpg?raw=true) 
*Blue = low (<30–100 ms), red = high/spiky (>200 ms)*

**Interference**  
![image](https://github.com/SeaBebop/Wifi-Heat-Map/blob/main/Wifi%20Heatmap%203-17-2026/WiFi%20Heatmap%20Interference%20Amount.jpg?raw=true)
*Alot of interferring networks, yet these red areas have the best singals. 5ghz is preventing interference issues*

### Recommendations / Next Steps
- Reposition AP to central living room ceiling/high wall for better omnidirectional coverage.
- Consider mesh nodes (one in hallway/kitchen) if drops persist.
- Test 2.4 GHz fallback for bathroom/kitchen reliability.
- Future: Re-run after changes + try a tool like [wifi-heatmapper](https://github.com/hnykda/wifi-heatmapper) for more precise overlays.
