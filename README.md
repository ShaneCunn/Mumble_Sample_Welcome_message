# Mumble MOTD: Message of the day
MOTD
Mumble.ini Message of the day, Example on how to make a Message of the Day (MOTD) on a Mumble server.

Instead of welcometext="Welcome to this server running Murmur."

-![alt text](http://i.imgur.com/Xm83rQk.png "Example Welcome message in mumble")

###Important links

* [Full Murmur.ini guide](http://wiki.mumble.info/wiki/Murmur.ini)

### HTML Examples in the Mumble.ini

Example logo in the welcome message:
 ```html
 <a href="https://www.google.com"><img alt="Your logo here" src="http://i.imgur.com/m4NsCG0.jpg" width="250"></a>
 ```
 
 Examples of an contact/Officer list:
 ```html
 <h3>Commanded by the best Officer's</h3>
<ul>
    <li><a href="https://www.google.com"><strong>Clan Leader:</strong> Clan leader</a></li>
    <li><a href="https://www.google.com"><strong>Officer 2:</strong> Co-leader</a>
    </li>
</ul>
```

Example of a line break
```html
<br>
```

Example of a hortizontal rule
```html
<hr>
```

### Example of Welcome message

[![Sample logo](http://i.imgur.com/m4NsCG0.jpg)](https://www.google.com)

### Commanded by the best officer's

*   [**Clan Leader:** Clan leader](https://www.google.com)
*   [**Officer 2:** Co-leader](https://www.google.com)

_***If you have any concerns please contact these Officers**_

* * *

### Latest Clan News and Events

*   [Example Link 1](https://www.google.com)
*   [Example Link 2](https://www.google.com)

* * *

### Please read these Threads to:

*   [Get full access to the Clan Forums](https://www.google.com)
*   [Suggestion on how to improve the Clan/Website please post them here](https://www.google.com)

* * *

### HTML example of a Welcome message
```html
welcometext="
<a href="https://www.google.com"><img alt="BRTD old logo" src="http://i.imgur.com/m4NsCG0.jpg" width="250"></a>
 <h3>Commanded by the best Officer's</h3>
<ul>
    <li><a href="https://www.google.com"><strong>Clan Leader:</strong> Clan leader</a>
    </li>
    <li><a href="https://www.google.com"><strong>Officer 2:</strong> Co-leader</a>
    </li>
</ul>
<p><em><strong>*If you have any concerns please contact these
  Officers</strong></em>
</p>
<br>
<hr>
 <h3>Latest Clan News and Events</h3>
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
      Clan/Website please post them here</a>
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
    </ul>
	"
```

Example of important message i.e. a disclaimer

## Legal Disclaimer

*   <span style="color:#ff0000">_**Please Be Aware It's an age 18+ Voice Server.**_</span>
*   <span style="color:#ff0000">_**By using this Voice Server you agree that you are aged 18 or older.**_</span>
*   <span style="color:#ff0000">_**The Server host takes no responsibility for context of conversations or messages sent or received on this server.**_</span>

### HTML Example of Legal Disclaimer
```html

<h3>Legal Disclaimer</h3>

<ul type="square">
     </li>
    <li><span style="color:#ff0000"><em><strong>Please Be Aware It's an age 18+
    Voice Server.</strong></em></span>
	</li>
    <li><span style="color:#ff0000"><em><strong>By using this Voice Server you
    agree that you are aged 18 or older.</strong></em></span>
    </li>
    <li><span style="color:#ff0000"><em><strong>The Server host takes no
    responsibility for context of conversations or messages sent or received on
    this server.</strong> <em></em></em></span>
  </ul>
```