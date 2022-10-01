<h1>TryHackMe - Corridor</h1><br>
<img src="./img/room-icon.png" alt="room-icon">
<h2>Reconnaissance</h2>
<ol>
    <li>
        Starting with rustscan.<br><br>
        <img src="./img/rustscan.png" alt="rustscan" width="400"><br>
    </li>
    <li>
        Explorig the WebPage.<br><br>
            &emsp;<img src="./img/webpage.png" alt="webpage" width="450"><br>
            &emsp;its a simple webpage with a lot of doors.<br><br>
            &emsp;<img src="./img/source-code.png" alt="source-code" width="550"><br>
            &emsp;And that it's endpoints are hased values of something. Let's crack them using crackstation<br><br>
            &emsp;<img src="./img/hashes.png" alt="hashes" width="400"><br>
            &emsp;the endpoints are MD5 hash values of numbers from 1 to 13.<br><br>
    </li>
    <li>
        Getting the flag.<br>
            &emsp;The room description suggests us to uncover website locations and also to look at the pattern for help so<br>
            &emsp;my next step is to write a python script that generates hash of numbers and test's weather they exist here.<br>
            &emsp;<img src="./img/python-script.png" alt="script"><br>
    </li>
</ol>

<!-- &nbsp; &nbsp; &nbsp; &nbsp; ![rustscan](./img/rustscan.png)  
&nbsp; &nbsp; &nbsp; &nbsp; Only one port is open. Let's check it out.  


&nbsp; &nbsp; &nbsp; &nbsp; <img src="./img/webpage.png" alt="web-page" width="200"/>  
&nbsp; &nbsp; &nbsp; &nbsp; It's a webpage with a lot of door's. Let's checkout the source code.  

&nbsp; &nbsp; &nbsp; &nbsp; ![source-code](./img/source-code.png)  
&nbsp; &nbsp; &nbsp; &nbsp; From the room's descriptoin, we know that these are hashes so lets check which one and crack them.  

&nbsp; &nbsp; &nbsp; &nbsp; ![hashes](./img/hashes.png)  
&nbsp; &nbsp; &nbsp; &nbsp; Hash-Identifier specified that these are MD5 hashes and crackstation result shows that these endpoints are MD5 values of numbers from 1 to 13.

## Exploiting  

#### We know the endpoints are hashes of numbers so my next step was to write a python script to find hidden endpoints.

##### Python Script  

![pythonScript](./img/python-script.png)  


<h1>Done</h1> -->
