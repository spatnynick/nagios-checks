# nagios-checks

My custom checks for nagios

<h2>check_lm_sensors_bogo</h2>
<p>This plugin checks hardware status using the lm_sensors package,
which needs to be correctly configure beforehand (command 'sensors' has to return data)</p>

<h2>check_if</h2>
<p>A plugin in bash designed to monitor router throughtput rate. Non-password (e.i. key-based) access to remote host is required. Returns up/down in MB, number of active connections and the system load.</p>

<h2>check_hdparm_C</h2>
<p>Checks whether specified disc is in standby (spin-down) or in active/idle (spin-up) mode.
I just like to see in my Nagios's graphs statistics of my discs spinup/down, e.g. to be able to check
whether my discs are not started too often</p>

Enjoy, Bohu


