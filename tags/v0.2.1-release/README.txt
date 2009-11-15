Multi-Language Translation Script
by Patrick Hathway, OdinLab, University of Reading
Version 0.2.1 [2009-11-15]

This script automatically translates a webpage (containing text in more than one language) into any 
single language requested by the user. This can be particularly useful for sites involving a lot of 
user-generated content (which might have originally been written by a number of users who speak
different native languages) - e.g. blogs, forums, or other community sites. The script harnesses 
the Google AJAX Language API to perform translation and language detection.

For more information about this script, please visit:

http://code.google.com/p/multi-language-translation/

From that website you will be able to view full documentation (including detailed usage instructions
and examples); as well as get the latest updates; request any changes or new features; report any 
bugs or problems; or make any other comments. All feedback is extremely welcome!


USAGE INSTRUCTIONS:


Below are some instructions describing very briefly how to deploy this script on your website:


1. Include the following 3 HTML lines somewhere on every webpage that uses the script:

<script type="text/javascript" src="http://www.google.com/jsapi"></script>
<script type="text/javascript" src="translate.js"></script>
<div id="languagelist"></div>

At this location of each page, a listbox will appear, allowing the user to change languages...

2. Open the file 'translate.js', and make the necessary configurations to the top of the script. 
The required changes are outlined within that file; and complete instructions/examples are shown 
in the full documentation [see the link above].

3. Upload the file 'translate.js' (as well as any changes made to any webpages in your site) to 
your server. Your work is complete!


The attached file 'example.htm' provides a very simple working example of the script in action.
Please ensure that you have extracted both 'example.htm' and 'translate.js' from the archive 
into a new folder before opening the example. View the source of 'example.htm' to see comments 
describing how the script interacts with the page. For further examples and much more detailed 
usage instructions, please check the full documentation.


SCRIPT LICENCE:


The MIT License

Copyright (c) 2009 Patrick Hathway, OdinLab, University of Reading

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and 
associated documentation files (the "Software"), to deal in the Software without restriction, 
including without limitation the rights to use, copy, modify, merge, publish, distribute, 
sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is 
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or 
substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING 
BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND 
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, 
DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, 
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


---


[IMPORTANT NOTE: Portions of this script directly interact with ("invoke") functionality of the 
Google AJAX Language API, which is governed by the AJAX API Terms of Use - see:
http://code.google.com/intl/en/apis/ajaxlanguage/terms.html
It is therefore Your responsibility to ensure that Your usage of this script on Your website 
fully complies with those terms. The developer of this script is in no way affiliated with Google. 
For more information, please see the full documentation.]


---


Thank you for your interest in this script. If you have any problems, questions, comments, 
or suggestions, please visit the website above and get in touch!


Patrick Hathway,
15th November 2009