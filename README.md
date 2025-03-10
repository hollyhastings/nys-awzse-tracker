# nys-awzse-tracker
Get and store the mobile deployment units posted by NYDOT/NYSTA's [Automated Work Zone Speed Enforcement (AWZSE) Program](https://www.ny.gov/work-zone-safety-awareness/automated-work-zone-speed-enforcement-program).

# Intro
New York State maintains a web page for their Automated Work Zone Speed Enforcement (AWZSE) Program.
This program uses radars and cameras to detect and identify speeding motor vehicles within a speed zone and sends a Notice of Liability" to the registered owner of that motor vehicle. More info about this program can be found on [the program's web page](https://www.ny.gov/work-zone-safety-awareness/automated-work-zone-speed-enforcement-program).

Locations of these detection sites are stored within a linked PDF file which makes it more difficult to programatically get the data. The PDF link and active dates are updated before or while the detection sites are active.

The web page only shows up-coming/current detection site deployments.

# Plan
## Phase 1 - Basics: Wrangling, Downloading, and Parsing
Get the base functionality working
- [ ] Download the PDF containing the most-recent locations
- [ ] Parse the table in the PDF to CSV (including information on direction and names of highways, if included)
## Phase 2 - Simple Automation
- [ ] Run all basic functionality automatically (Github Actions?)
- [ ] Improve "Location" parsing to get a more specific location (maybe even mappable?)
## Phase 3 - Maturation
TBD
