# Popular Icon Packages JSON
This contains several JSON files that have all the icons included for certain popular CSS Icon frameworks. This was needed for a project and I felt like others might find it useful as well.

## The JSON Files
### [Font Awesome 4.7 Icon JSON File](font_awesome_4_7_0.json)
The JSON has several ways that the icons are categorized. I would not suggest using the entire JSON file, just pull out the array or object that you want as there is quite a bit of redundancy. I used [this page](https://fontawesome.com/v4/icons/) to scrape the data that created the file on 2-FEB-2025. 
The main object includes the following keys:
* byCategory - This is a object where the keys are the categories / sections listed on the scraped page with each icon in that section in an array.
* justIcons - This is just one array of all the icon classes in the array
* detailedIcons - This is an array of objects. Each object represents one of the icons and includes the keys for the class, category and the "descriptive" name of the icon

## [Bootstrap Glyph Icons 1.11.3 JSON File](bootstrap_glyph_icons_1_11_3.json)
Each key in this object is a CSS class that represents a icon. Each key is an object that has a name, which is the CSS class name, tags and a category. 

## [Bootstrap Glyph Icons 3.4.x JSON File](bootstrap_glyph_icons_3_4.json)
This is just a single array of all the free icons class names.