# in-class-activities
## Devlogs
### W1
Write your W1 activity Devlog here.
"Hello world!"

### W2
1. They are floats because Unity's Color uses values from 0.0 to 1.0 for each channel, and we change them by small decimal steps like 0.1f. Ints, bools, or strings cannot represent these smooth changes in brightness.
2. "_bounces" is an int because it counts whole collisions: 1 bounce, 2 bounces, etc., not halves. Technically, float also can be used, but using an int also makes simple updates like _bounces++ clear and safe.
3. The error said we mixed number types: we used a double literal 0.1 with a float variable g. The fix is to use a float literal and write g -= 0.1f;, so the types match.

### W3
Tables 7-13
Input should be an integer type since it involves friendship level and whether or not the player knows the character's secret.
On the other hand, output should be a String since it involves the character's text.

### W4
Table 1-10
#### Activity 1
Line 5: The float variable for moving speed can be modified in the inspector
Line 22: The float variable for moving distance is the sum of vertical input, move speed, and time
Line 25: Move the character by the amount calculated along the z-axis
#### Activity 3


## Open-Source Assets
### W1
- Animals: https://assetstore.unity.com/packages/3d/characters/animals/animals-free-animated-low-poly-3d-models-260727 
- Low-poly environment: https://assetstore.unity.com/packages/3d/environments/landscapes/low-poly-simple-nature-pack-162153 