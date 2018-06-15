# pi_speedtest
Simple internet speed logging script for raspberry pi.

Works the same as a command line request for a speed test using speedtest-cli.

Needs the following install to work:
pip install speedtest-cli

Lines that would normally print are commented out.

This is typically used in conjunction with a cronjob.
eg. sudo python /home/pi/speedtest2.py >> /home/pi/speedtest/speedtest.csv

