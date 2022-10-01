<h1>TryHackMe - Corridor</h1><br>
<img src="./img/room-icon.png" alt="room-icon">
<h2>Reconnaissance</h2>
<ol>
    <li>
        Starting with rustscan.<br><br>
        <img src="./img/rustscan.png" alt="rustscan" width="400"><br>
        Theres only one port open. Let's check it out.
    </li><br>
    <li>
        Explorig the WebPage.<br>
            &emsp;<img src="./img/webpage.png" alt="webpage" width="450"><br>
            &emsp;its a simple webpage with a lot of doors.<br><br>
            &emsp;<img src="./img/source-code.png" alt="source-code" width="550"><br>
            &emsp;And that it's endpoints are hased values of something. Let's crack them using crackstation<br><br>
            &emsp;<img src="./img/hashes.png" alt="hashes" width="400"><br>
            &emsp;the endpoints are MD5 hash values of numbers from 1 to 13.<br>
    </li>
    <li>
        Getting the flag.<br>
            &emsp;The room description suggests us to uncover website locations and also to look at the pattern for help so<br>
            &emsp;my next step is to write a python script that generates hash of numbers and test's weather they exist here.<br>
            &emsp;<img src="./img/python-script.png" alt="script"><br>
            &emsp;And just as i expected, i got an endpoint where i got the flag.<br><br>
    </li>
</ol>