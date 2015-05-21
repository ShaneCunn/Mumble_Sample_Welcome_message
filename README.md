# BRTD-Mumble
MOTD
Mumble.ini Message of the day,  How to make a nice Message of the Day(MOTD) in Mumble.

Instead of welcometext="Welcome to this server running Murmur."

-![alt text](http://i.imgur.com/Xm83rQk.png "Example Welcome message in mumble")

### Html Example  in Mumble ini

Example logo in the welcome message:
 ```html
 <a href="http://goo.gl/0a6Ok4"><img alt="BRTD old logo" src="http://i.imgur.com/m4NsCG0.jpg" width="250"></a
 ```
 
 Examples of an contact/Officer list:
 ```html
 <h3>Commanded by the best Officer's</h3>
<ul>
    <li><a href="https://www.google.com"><strong>Clan Leader:</strong> Outfit leader</a></li>
    <li><a href="https://www.google.com"><strong>Officer 2:</strong> Co-leader</a>
    </li>
</ul>
```
Example of line break and hortizontal rule
```html
<br>
<hr>
```
Example of import message ie Disclaimer and so on
```html
<h3>Legal Disclaimer</h3>

<ul type="square">
    <li style="list-style: none"><span style="color:#ff0000"><em><strong></strong></em></span>

    </li>
    <li><span style="color:#ff0000"><em><strong>Please Be Aware It's an age 18+
    Voice Server.</strong></em></span>

    </li>
    <li style="list-style: none"><span style="color:#ff0000"><em><strong></strong></em></span>

    </li>
    <li><span style="color:#ff0000"><em><strong>By using this Voice Server you
    agree that you are aged 18 or older.</strong></em></span>

    </li>
    <li style="list-style: none"><span style="color:#ff0000"><em><strong></strong></em></span>

    </li>
    <li><span style="color:#ff0000"><em><strong>The Server host takes no
    responsibility for context of conversations or messages sent or received on
    this server.</strong> <em></em></em></span>
  </ul>
```
### Full example of Welcome message
```html
welcometext="<a href="https://www.google.com"><img alt="BRTD old logo" src="http://i.imgur.com/m4NsCG0.jpg" width="250"></a>

 <h3>Commanded by the best Officer's</h3>

<ul>
    <li><a href="https://www.google.com"><strong>Clan Leader:</strong> Outfit leader</a>

    </li>
    <li><a href="https://www.google.com"><strong>Officer 2:</strong> Co-leader</a>

    </li>
</ul>
<p><em><strong>*If you have any concerns please contact these
  Officers</strong></em>

</p>
<br>
<hr>
 <h3>Latest Outfit News and Events</h3>

<ul>
    <li> <a href="https://www.google.com">Example Link 1</a>

    </li>
    <li> <a href="https://www.google.com">Example Link 2</a>

    </li>
</ul>
<hr>
 <h3>Please read these Threads to:</h3>

<ul>
    <li> <a href="https://www.google.com">Get full access to the Clan Forums</a>

    </li>
    <li> <a href="https://www.google.com">Suggestion on how to improve the
      Outfit/Website please post them here</a>

    </li>
</ul>
<hr>
 <h3>Legal Disclaimer</h3>

<ul type="square">
    <li style="list-style: none"><span style="color:#ff0000"><em><strong></strong></em></span>

    </li>
    <li><span style="color:#ff0000"><em><strong>Please Be Aware It's an age 18+
    Voice Server.</strong></em></span>

    </li>
    <li style="list-style: none"><span style="color:#ff0000"><em><strong></strong></em></span>

    </li>
    <li><span style="color:#ff0000"><em><strong>By using this Voice Server you
    agree that you are aged 18 or older.</strong></em></span>

    </li>
    <li style="list-style: none"><span style="color:#ff0000"><em><strong></strong></em></span>

    </li>
    <li><span style="color:#ff0000"><em><strong>The Server host takes no
    responsibility for context of conversations or messages sent or received on
    this server.</strong> <em></em></em></span>
    
</ul>"


```
