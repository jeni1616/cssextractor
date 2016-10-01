# CSS extractor
extract css code with specific property

READ THIS BEFORE STARTING

you have to run this script on server , it can not work on file:// protocol so make sure to either use localhost or some server setup to run this script , for localhost you may use mamp OR xaamp or wamp or any other localhost application which support php . the script login is written in php .

feature : 

JUST FORMAT YOUR CODE ON http://www.codebeautifier.com/ and than paste result code in this cssextractor input text box , hit submit and you should get result in right side output box .

in future i may add more css selector choice but if you need it currently than just edit it.php file of this project and from line #63-67 you should see :

<code>
if (0 === strpos($key, 'back')) {
$tempstring.= $key.';';
}
if (0 === strpos($key, 'colo')) {
$tempstring.= $key.';';
}
</code>

as you see , i have checked for background and color property but you may copy this condition and add your own selector choice :)
