Hello, All.

".DevColors" is meant as an example to show a surface level
way of changing the scrollbar's color in the Opera Browser.

Both the content.js file & the styles.css file apply its own scrollbar.
So there's two scrollbars on the screen, one injected - red, and one stylesheet -blue.

You must supply a "width:" for the "-webkit-scrollbar" or the color 
changes won't work.

The "matches" within the manifest.json defines where you want to 
display these changes, or don't want to display them.

(Install:)

(1): Open the Opera browser.
(2): Ctrl + Shift + E .
(3): Toggle "Developer Mode" on, it's next to the search extensions bar.
(4): Load unpacked.
(5): Select the folder "unpkd_DevColors".
(6): Set "Allow access to search page results" to true.

(Test:) 

Go to a webpage with a scrollbar. If it's working; you'll
see a red bar, and a blue bar if you refresh.


-  IM-EVIL




I suggest putting "unpkd_DevColors" in your Opera profile folder.
Type "about:" into Opera's address bar to find the location.

Don't put "unpkd_DevColors" in the extensions folder or Opera will remove it.

(manifest.json - "match")
https://developer.chrome.com/docs/extensions/mv3/match_patterns/

(manifest.json)
https://developer.chrome.com/docs/extensions/mv3/manifest/

