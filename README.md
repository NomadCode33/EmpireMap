# Map of New York
Labeled a street map of New York by employing label classes and utilizing queries to target and label specific subsets of features. Additionally, I created an optimized layout for the map, ensuring clear and effective presentation.

<img src="./New York.jpg" img alt = "New York Map"/>

## How It's Made:

**Tech used:** ArcGIS Pro

The map starts off as a jubbled mess of labels that need to be sorted accordingly. The first step is to label the border line running through the Hudson River between the states of New York and New Jersey. I selected the State Line layer in the Contents pane and turned on the labels. A single line feature runs through the Hudson River to represent the border between the two states in the map so I have give the line a unique label to indicate which side of the line is the state of New York and which side is the state of New Jersey. From the Labeling tab, in the Label Class group, I clicked the Class down arrow and chose Create Label Class. In the Create New Label Class dialog box, I typed Below for the name and this class will be used for the New York label. There is already a Class available called Class 1 so I selected it in the Label Class pane renamed the class Above for the New Jersey label to make it more understandable. I made sure that the class is set to Above and clicked the Field down arrow and chose the RIGHT_NAME10 field and set the text appearance to certain parameters.

Since the Above symbol class is created, I can save it as a symbol style to apply it in the other State Lines class. In the Label Class pane, from the Symbol tab, I clicked the Menu button and chose Save Symbol to Style . After setting up the style symbol and naming it State Line Text Symbol, it appears in the Text Symbol group on the Labeling tab. I then clicked the Postion tab for the Above label class in the Label Class pane to change some placement and position settings and save those settings to another style. After setting the text positon style and saving as State Line Label Placement, it then appears in the Label Placement group. From the Labeling tab, in the Label Class group, I changed the Class field to Below. In the Text Symbol group, I chose the State Line Text Symbol style. In the Label Placement group, chose the State Line Label Placement. Then in the Label Class pane, from the Position tab, changed the COnstrain Offset placement value to Below Line.

## Lessons Learned:

No matter what your experience level, being an engineer means continuously learning. Every time you build something you always have those *whoa this is awesome* or *wow I actually did it!* moments. This is where you should share those moments! Recruiters and interviewers love to see that you're self-aware and passionate about growing. A single line feature runs through the Hudson River to represent the border between the two states in the map so I have give the line a unique label

## Repositories
**Profile:** [T3ch12et](https://github.com/T3ch12et)

**Cartography Repository:** [ESRI MOOC Cartography](https://github.com/T3ch12et/GIS-Data-Science-Portfolio/tree/main/ESRI-MOOC-Cartography)

**Main Repository:** [GIS Data Science Portfolio](https://github.com/T3ch12et/GIS-Data-Science-Portfolio)

## Examples:
Take a look at these couple examples that I have in my own portfolio:

**Palettable:** https://github.com/alecortega/palettable

**Twitter Battle:** https://github.com/alecortega/twitter-battle

**Patch Panel:** https://github.com/alecortega/patch-panel
