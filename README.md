# Smart Health Fracture Detection Dataset (VOC+YOLO) - 437 Images in 4 Categories

**Dataset Format:** Pascal VOC format + YOLO format (txt file without split path, only containing jpg images and corresponding VOC-format xml files and YOLO-format txt files)

**Number of Images (jpg Files):** 437

**Number of Annotations (xml Files):** 437

**Number of Annotations (txt Files):** 437

**Number of Categories:** 4

**Category Names for Annotations (Note that the order in YOLO format does not correspond with this, but is based on the labels folder "classes.txt"):** ["angle", "fracture", "line", "messed_up_angle"]

**Box Counts per Category:**

- angle (Angle) Boxes = 41
- fracture (Break) Boxes = 326
- line (Line) Boxes = 164
- messed_up_angle (Messed Up Angle) Boxes = 70

**Total Boxes:** 601

**Boxes per Image for Each Category:**

- angle (Angle) Image Count = 34
- fracture (Break) Image Count = 221
- line (Line) Image Count = 133
- messed_up_angle (Messed Up Angle) Image Count = 66

**Image Resolution:** 640x640

**Annotation Tool:** labelImg

**Annotation Rules:** Draw a box around the category

**Important Notice:** The dataset does not have been divided into training, validation, or test sets; you need to do so yourself.

**Special Disclaimer:** This dataset does not guarantee any accuracy in the trained model or weight files.

**Image Preview:**

![codep](codep.png)

