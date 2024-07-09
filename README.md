# VMPS
 Musica's VTOL Mission Planning Software

For alpha releases, keep in mind that when you create a new campaign it will be placed in your temp folder.

# How to use:

1. File > New Campaign...
 - Enter a campaign name, then choose the folder where your campaign lives.
2. File > Open Campaign...
- Should be in your temp folder path that opens when you go Open Campaign. If you want to keep up with this file, I recommend dragging to the desktop.
3. Choose Scenario button on the bottom left corner.
4. Choose Map... button if you plan on building off the map, otherwise, press the Unit -> Template button to replace your units with templates.
5. Import Templates button will allow you to choose the folder where your templates live for import.
  - For template creation, the first line must be z_threshold = 0.0 (or any other floating number)
  - z_threshold is the ground height at which your template was created.
  - The next lines will be UnitSpawner objects and StaticObject objects.
6. Place your templates to your heart's contect
7. When you're ready to save, use File > Save as... or File > Save

# NOTES:
- In this early alpha build, you must have at least one unit, and one static object in scenario that you're copying templates to.


 HAPPY HUNTING!
