What is this?
=============

This repo contains common git settings you can easily include in your configuration

HOWTO
=====
Installation includes two easy steps:<br/>
1. Clone the repository<br/>
2. Include selected settings files into your configuration. <br/>
 
Example:<br/> 
To add common command aliases to user-wide git configuration open .gitconfig file from your home folder then add following line:
<pre><code>
$> edit ~/.gitconfig
    [include]
        path = [REPLACE_WITH_REAL_PATH_TO_THE_FILE]/gitconfig-alias    
</code></pre>