<h1>8-bit Tweet<em>it</em></h1>
<img src="https://raw.githubusercontent.com/MadArkitekt/8bit-Tweetit/master/8bitStatus/Images.xcassets/AppIcon.appiconset/Icon-60@2x.png">
<hr>
<h3>Tweet using *"The O.G. of Emoji"* in all of their 8-bit glory!<h3>
<p>
-Simply select you favorite color amongst the group, the face corresponding to your mood, and then you'll reach screen below whereupon you can Tweet<em>it</em>, or not. (see <a href="http://edsalter.co"> my portfolio</a> for more screenshots)</p>
(aaaand, another awesomely large screenshot)
<img src="https://raw.githubusercontent.com/MadArkitekt/MadArkitekt.github.io/master/assets/images/8bit@2x.png">
(the face seems quite surprised... at it's largeness... ANYWAYS)
<hr>
<h3>Construction and UI Elements</h3>
<p>
-The smilies themselves are made in Adobe Illustrator (I've included a template or sorts, so you can create your own)<br>
-Each grid of 9 items is built by using fast enumeration for loops to iterate through arrays of images.
-Current selection is displayed by a light-gray marker surrounding the chosen item
-Selections are encapsulated in a singleton property. Said singleton also houses the switch statement containing all arrays of faces.
* I've found singleton properties superior to the delgate pattern and more wieldy in smaller projects such as this app. Should the app be more multifaceted, or contain JSON serialization / multiple interactions with a remote database, I'd rather institute a notification center to maintain tighter control over which entities can "see" certain data.
