# EX No.3.2. CREATE 3D MODEL FROM ORTHOGRAPHIC PROJECTION
## DATE:
## AIM:
To create a 3D model from given orthographic projection.

## REQUIREMENTS:
1. Autodesk fusion 360
2. Windows 10
3. 16 GB of RAM (integrated graphics recommend 1 GB or more)
4. 2.5 Mbps or faster download; 500 Kbps or faster upload 

## PROCEDURE:
### Step 1: Base plate

1. Open Fusion 360 and select the **Design → Solid** workspace.
2. Click **Create Sketch** and select the Top (XY) plane.
3. Choose **Sketch → Rectangle → Two-Point Rectangle**.
4. Draw the central rectangular base profile with a length of 300 mm and a width of 150 mm.
5. Position the rectangle symmetrically about the origin.
6. Click **Finish Sketch**.
7. Select **Extrude**, choose the rectangular profile and enter 30 mm as the extrusion distance.
8. Press Enter to create the base plate.

### Step 2: Rounded end mounting plates

9. Start a new sketch on the top face of the base plate.
10. Choose **Sketch → Circle → Center Diameter Circle**.
11. Draw a circular profile of diameter 120 mm (R60) at the left end of the base.
12. Position the centre of the circle 150 mm from the origin along the length of the component.
13. Repeat the same procedure at the right end, placing the second circle 150 mm from the origin in the opposite direction.
14. Use the required connecting lines and trimming operations to form the rounded mounting ends, maintaining the overall length of 420 mm.
15. Click **Finish Sketch**.
16. Select **Extrude** and extend the mounting plate profiles by 30 mm, using **Join** to combine them with the base.

### Step 3: Create the arched support

17. Click **Create Sketch** and select the Front (XZ) plane.
18. Choose **Sketch → Arc → Center Point Arc**.
19. Place the arc centre at the origin and construct a semicircular arc with a radius of 110 mm (R110).
20. Draw two vertical lines from the ends of the semicircular arc to form the supporting sides.
21. Connect the lower ends of the vertical lines to complete the closed arch profile.
22. Use the **Dimension** tool to maintain an inner opening width of 120 mm as indicated in the drawing.
23. Click **Finish Sketch**.
24. Select **Extrude**, choose the closed arch profile and enter 150 mm as the extrusion distance.
25. Select **Join** as the operation to connect the arched support to the base structure.
26. Press Enter to create the arched support.

### Step 4: Create the rectangular opening

27. Start a new sketch on the Front face of the arched support.
28. Choose **Sketch → Rectangle → Two-Point Rectangle**.
29. Draw the rectangular opening at the lower central portion of the support.
30. Set its width to 120 mm as specified in the front view.
31. Position the opening symmetrically about the centre line.
32. Click **Finish Sketch**.
33. Select **Extrude**, choose the rectangular profile and select **Cut** as the operation.
34. Extend the cut through the required width of the support and press Enter.

### Step 5: Create the mounting holes

35. Select the top face of the left rounded mounting plate and click **Create Sketch**.
36. Choose **Sketch → Circle → Center Diameter Circle**.
37. Place the circle at the centre of the mounting plate.
38. Enter 40 mm as the diameter (Ø40).
39. Click **Finish Sketch**.
40. Select **Extrude**, choose the circular profile and select **Cut**.
41. Extend the cut through the entire thickness of the mounting plate.
42. Repeat the same procedure on the right mounting plate to create the second Ø40 hole.

### Step 6: Create the central hole

43. Select the top face of the central base portion and click **Create Sketch**.
44. Choose **Sketch → Circle → Center Diameter Circle**.
45. Place the circle at the centre of the base plate.
46. Enter 20 mm as the diameter (Ø20).
47. Click **Finish Sketch**.
48. Select **Extrude**, choose the circular profile and select **Cut**.
49. Extend the cut through the thickness of the base plate and press Enter.

### Step 7: Final inspection and drawing

50. Use the **Orbit** tool to inspect the completed model from different directions.
51. Verify the overall length of 420 mm and the width of 150 mm.
52. Check the arch radius of 110 mm and the central opening width of 120 mm.
53. Verify the rounded mounting ends with a radius of 60 mm.
54. Check the two mounting holes of diameter 40 mm and the central hole of diameter 20 mm.
55. Ensure that all the features are properly joined and that the required openings are created.
56. Save the completed model.
57. Generate the front, top and end views along with the isometric view using the Drawing workspace.
58. Add the necessary dimensions, centre lines and hidden lines to complete the engineering drawing.
## INPUT:
![image](https://user-images.githubusercontent.com/113594316/198823540-38a1b79a-1f68-4876-add9-adf59b98b386.png)

## OUTPUT:
<img width="975" height="695" alt="Screenshot 2026-11-15 184841" src="https://github.com/user-attachments/assets/8f8c782d-5bf0-4483-a2d5-624ebd8c0b0e" />



## RESULT:
Thus, 3D model is created from orthographic projection.



