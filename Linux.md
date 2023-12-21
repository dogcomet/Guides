Find large log files.
Example:
sudo find /opt/* -type f -size +800M | grep log_name.log




This will help you find the most recent updates by tailng the app history log.
tail -n250 /var/log/apt/history.log
