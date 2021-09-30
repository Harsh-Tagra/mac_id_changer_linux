# mac_id_changer_linux
<h3>use below commands to run</h3>
<h4>1. give permmision
  </h4>
<h5>chmod u+r+x ./macIdChanger.sh</h5>

<h4>2.run sh file </h4>
<h5>./macIdChanger.sh</h5>
<h3>use below commands to set on startup linux <h3>
<h4>1. first edit crontab file
  </h4>
  <h4> crontab -e</h4>
  <h6> after open file enter few lines at top without change any line</h6>
  <h4>@reboot /home/harsh/Desktop/h.sh<h4>
    <h3>2.start corn service </h3>
    <h4>service cron start</h4>
    <h3>3.now set cron on start services</h3>
    <h4>systemctl start cron.start</h4>
    <h3>4.now start stsrt cron service on start</h3>  
    <h4>systemctl start cron.service</h4>
<h3> 5. upadte crone on start deafaltus</h3>
<h4>  update-rc.d cron defaults</h4>
<h3> now reboot sysytem</h3>

