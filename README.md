# nys-awzse-tracker
Get and store the mobile deployment units posted by NYDOT/NYSTA's [Automated Work Zone Speed Enforcement (AWZSE) Program](https://www.ny.gov/work-zone-safety-awareness/automated-work-zone-speed-enforcement-program).

# Intro
New York State maintains a web page for their Automated Work Zone Speed Enforcement (AWZSE) Program.
This program uses radars and cameras to detect and identify speeding motor vehicles within a speed zone and sends a Notice of Liability" to the registered owner of that motor vehicle. More info about this program can be found on [the program's web page](https://www.ny.gov/work-zone-safety-awareness/automated-work-zone-speed-enforcement-program).

Locations of these detection sites are stored within a linked PDF file which makes it more difficult to programatically get the data. The PDF link and active dates are updated before or while the detection sites are active.

Previous detection site data is not available on the web page as it only shows up-coming/current detection site deployments.

# Plan
## Phase 1 - Basics: Wrangling, Downloading, and Parsing
Get the base functionality working
- [ ] Locate the most-recent date range for the report (highly variable format, web page only)
- [ ] Download the PDF containing the most-recent locations
- [ ] Parse the table in the PDF to CSV
## Phase 2 - Simple Automation
- [ ] Run all basic functionality automatically (Github Actions?)
## Phase 3 - Maturation
TBD
