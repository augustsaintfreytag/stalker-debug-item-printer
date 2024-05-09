# STALKER Debug Item Printer

A utility script for STALKER Anomaly (Open X-Ray/Monolith) that reads through all registered items in the game and compiles a Markdown table for all items and their properties. Also tries to determine the intended primary use of an item by comparing its data and picking significants. Intended for mod developers to get a grand view of the final state of registered items and to ease the creation of DLTX patches. Intended for STALKER Anomaly and its derivatives.

## Usage

- Install mod via MO2 or manually by placing it into game root directory
- Load a level (loading debug level recommended, press F2 in main menu)
- Quit game after loading has finished
- Find `saint_item_data.md` in output directory

Depending on your set-up, the output directory may be one of the following:

- `<MO2 Directory>/overwrite/bin/saint_item_data.md`
- `<Game Directory>/bin/saint_item_data.md`

## Output

The output Markdown file has one section for each item. It resolves the localized name of every section to use as a heading (e.g. a heading for `glucose_s` will be `Glucose Shot`). The configured properties appear as rows in *Property, Value* form. Both string and numeric values are supported as values in the table.

![Debug Printer Example 03](https://github.com/augustsaintfreytag/stalker-debug-item-printer/assets/7656669/d14f9cb7-ea48-4c09-966d-361fc250e0e6)

## License

This mod is licensed under MIT with basic attribution for free use and distribution by the STALKER mod community.
