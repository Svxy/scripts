<h1 align=center>Javascript - TnyavnTo</h1>

<br>

<p align=center><sup>Check out my <a href='https://tnyavnto.com' target='_blank'>portfolio</a> if you happened to have found this page elsewhere.</sup></p>

<br><br>

<p align=center>
    <img src='https://github.com/Svxy/imgs/blob/main/icon.png?raw=true' alt='Github Couldnt Load The Image'>
</p>

<br><br>

<h3 align=center>Heres my list of Batch Scripts</h3>

<br><br>

<!-- Network -->

<p align=center>Check Network Connection:</p>

<p align=center>
<pre>
<code class="batch"> 
@echo OFF
color 0A
title Check connection
cls
echo please wait ...

ping -n 1 www.google.com >nul
if not errorlevel 1 goto :noerror
if errorlevel 1 goto :error

:noerror
echo Connection successful !
pause >nul

:error
echo No connection :(
pause >nul
</code>
</pre>
</p>

<br><br>

<p align=center>Check Network Port:</p>

<p align=center>
<pre>
<code class="batch"> 
@echo OFF
title Check port
color 0A
cls
echo please wait ...
netstat -ano
tasklist|findstr "9999"
pause >nul
</code>
</pre>
</p>

<br><br>

<p align=center>FTP Load:</p>

<p align=center>
<pre>
<code class="batch"> 
::Run as Administrator
@echo OFF
title FTP load
color 0A
ftp
exit
</code>
</pre>
</p>

<br><br>

<p align=center>Netstat:</p>

<p align=center>
<pre>
<code class="batch"> 
::Run as Administrator
@echo OFF
title Netstat
color 0A
echo please wait ...

netstat -a                         
netstat -e                           
netstat -n                           
netstat -o                           
netstat -p                           
netstat -s
netstat -r
pause > nul
</code>
</pre>
</p>

<br><br>

<!-- System -->

<br><br>

<p align=center>Check disk:</p>

<p align=center>
<pre>
<code class="batch"> 
::Run as Administrator
@echo OFF
title Check disk
color 0A
chkdsk
pause >nul
</code>
</pre>
</p>

<br><br>

<p align=center>Gpresult:</p>

<p align=center>
<pre>
<code class="batch"> 
::Run as Administrator
@echo OFF
title Gpresult
color 0A
gpresult /z
pause >nul
</code>
</pre>
</p>

<br><br>

<p align=center>System info:</p>

<p align=center>
<pre>
<code class="batch"> 
@echo OFF
title System info
color 0A
systeminfo
pause >nul
</code>
</pre>
</p>

<br><br>

<p align=center>IPConfig:</p>

<p align=center>
<pre>
<code class="batch"> 
@echo OFF
title IP config
color 0A
ipconfig /all
pause > nul
</code>
</pre>
</p>

<br><br>

<p align=center>Task list:</p>

<p align=center>
<pre>
<code class="batch"> 
@echo OFF
title Task List
color 0A
tasklist
pause >nul
</code>
</pre>
</p>

<p align=center>Read our <a href='https://tnyavnto.com/policy/' target='_blank'>privacy policy</a></p>