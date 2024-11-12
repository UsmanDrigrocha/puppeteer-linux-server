# puppeteer-linux-server

### puppeteer in linux ; packages 
``` apt-get install libgtk2.0-0t64 libgtk-3-0t64 libgbm-dev libnotify-dev libnss3 libxss1 libasound2t64 libxtst6 xauth xvfb ```  <i>only to install once</i> 
<br>
### Server load 
``` mpstat 1 1 | awk '/Average:/ {print 100-$NF}' ``` <i>server load in %</i> 

### server internet speed
```sudo apt install speedtest-cli``` <i>only to install once</i> <br><br>
``` speedtest-cli ``` <i>speed in MegaBits</i> <br><br>
```speedtest-cli --bytes ``` <i>speed in megabytes</i> <br><br>


```git reset --hard origin/master``` <i>// work like git pull -f</i>
<br><br>
```git clone git@github.com:<username>/<repo>.git``` // git clone 
