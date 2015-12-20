# moodle-emojis

Standard unicode emojis for moodle Atto editor

How to add the emojis to your moodle:
1. Create the /pix_core directory in your theme. It should be something like: /Your_Moodle_Site/theme/Your_Theme/pix_core
2. Copy the /s directory on it
3. Go to Administration > Site administration > Plugins > Filters > Manage filters
4. Enable 'Display emoticons as image'
5. Add the 'Emoticons' button to the Atto editor in Administration > Site administration > Plugins > Text editors > Atto HTML editor > Atto toolbar settings and enter emoticon = emoticon in the 'Toolbar Config' text box.
6. Purge Cache
7. You should be able to inser an emoticon from the Atto editor.
