# kc_timeline
Timeline program for KC

## Instructions
- **Generating the plot** - Run kc_timeline_program and it will generate a 'timeline.png' based on the data in 'kc_data.json'
- **Adding Data** - Open kc_data.json and add your data in the same format. Becare of the apostrophes: "" and ''. DO NOT DELETE THE BRACKETS: [] or {}
- **Change Graph Title** - open kc_paramfile.py and just change the value `chart_title = 'KC'` to `chart_title = 'WHATEVER YOU WANT'`

## Build Instructions
Built using pyinstaller. Make sure to include 'kc_data.json' and 'kc_paramfile.py' along with the release.
