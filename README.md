# Recursively-remove-all-adjacent-duplicates

Question >>
Given a string, recursively remove adjacent duplicate characters from the string. The output string should not have any adjacent duplicates. See following examples.

Examples >>

nput: azxxzy 
Output: ay 
First “azxxzy” is reduced to “azzy”. 
The string “azzy” contains duplicates, 
so it is further reduced to “ay”.
Input: geeksforgeeg 
Output: gksfor 
First “geeksforgeeg” is reduced to 
“gksforgg”. The string “gksforgg” 
contains duplicates, so it is further 
reduced to “gksfor”.
Input: caaabbbaacdddd 
Output: Empty String
Input: acaaabbbacdddd 
Output: acac 
