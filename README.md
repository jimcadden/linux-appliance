linux-appliance
===============

scripts to build linux appliances based on the local system kernel / libraries 

Instructions:

Step 1: Create an empty appliance 

  $> sudo ./linux-appliance/newapp myapp

Step 2: Add additional binaries to your appliance

  $> sudo ./linux-appliance/addapp myapp.d /usr/bin/time

Step 3: Build initrd from appliance root filesystem

  $> sudo ./linux-appliance/buildapp myapp.d
