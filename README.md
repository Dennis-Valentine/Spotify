# Spotify
I have a lot of downloaded songs and podcasts on spotify. I want to remove them but the UI is very slow. I'll use the API to automatically remove them. 

This is a 2 step process: first get a list of all the tracks in my library (one app to do this) and then remove it (another app to do this). 2 apps are used because the scope/permission for the first one is limited (but well documented). __This code was written on 9th Oct 2020.__

This script is open source, but requires a separate script with the user's credentials to actually run. The required variables are outlined in the R script.

- `R` contains the R scripts
- `data` contains the cleaned data
- `images` contains the graphs generated (plots/images)
- `refs` contains the references cited
- `tmp` scratch space for intermediate files. `tmp` is added to .gitignore
