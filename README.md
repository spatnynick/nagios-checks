# nagios-checks

My custom checks for nagios

<h2>check_lm_sensors_bogo</h2>
<p>This plugin checks hardware status using the lm_sensors package,
which needs to be correctly configure beforehand (command 'sensors' has to return data)</p>


<h2>check_hdparm_C</h2>
<p>Checks whether specified disc is in standby (spin-down) or in active/idle (spin-up) mode.
I just like to have stored in Nagios graphs statistids of my spinup/down, e.g. to be able to check
whether my discs are not spinned-up too often</p>

Enjoy, Bohu


