#!/bin/bash

scsin=$(ls -l /sys/class/scsi_host/ | wc -l)

for((i = $scsin; i >= 1; i--))

do

echo "- - -" > /sys/class/scsi_host/host$i/scan

    sleep 2

done
