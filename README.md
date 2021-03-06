# moodle-emojis

Standard unicode emojis for moodle Atto editor

How to add the emojis to your moodle:

 1. Create the '/pix_core' directory in your theme. It should be something like: /YourMoodleSite/theme/YourTheme/pix_core
 2. Copy the /s directory on it: /YourMoodleSite/theme/YourTheme/pix_core/s
 3. Go to Administration - Site administration - Plugins - Filters - Manage filters and enable 'Display emoticons as image'
 4. Add the 'Emoticons' button to the Atto editor in Administration - Site administration - Plugins - Text editors - Atto HTML editor - Atto toolbar settings and enter 'emoticon = emoticon' (without quotes) in the Toolbar Config text box.
 5. Purge Cache 

You should be able to insert an emoticon from the Atto editor.

**Tip:** The default size is 15x15px. You can change it adding this style in the Custom CSS: 

`img.emoticon {height: XXpx; width: XXpx;}`

where xx is the size and must be the same for both values.


**License**

Icons provided free by <http://emojione.com/>

Under Creative Commons Attribution 4.0 International
http://creativecommons.org/licenses/by/4.0/
