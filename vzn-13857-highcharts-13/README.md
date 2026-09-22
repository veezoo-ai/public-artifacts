# VZN-13857 - Highcharts 11 to 13 upgrade, visual comparison

Screenshots from the local toy knowledge graph used in the PR description. Each sheet shows, left to right:
master on Highcharts 11.4.6, the upgrade branch before its rendering fixes, and the upgrade branch after them.
"Dark mode" images were captured with the OS color scheme set to dark.

## ui/

Screenshots and Playwright recordings (WebM) of the scripted UI pass on the upgrade branch at Highcharts 13.1.0:
Modify Visualization editor, chart interactions (tooltips, zoom, legend, map navigation, drill-down) and a board
under window resizes, fullscreen and print emulation. The same scripts were run on master with Highcharts 11.4.6
and produced identical results.
