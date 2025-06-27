**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-f2/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONFUNCTION" is not known.
[pkrvmbietmlfzoi:68247] *** Process received signal ***
[pkrvmbietmlfzoi:68247] Signal: Aborted (6)
[pkrvmbietmlfzoi:68247] Signal code:  (-6)
[pkrvmbietmlfzoi:68247] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd58e645330]
[pkrvmbietmlfzoi:68247] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd58e69eb2c]
[pkrvmbietmlfzoi:68247] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd58e64527e]
[pkrvmbietmlfzoi:68247] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd58e6288ff]
[pkrvmbietmlfzoi:68247] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd58eaa5ff5]
[pkrvmbietmlfzoi:68247] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd58eabb0da]
[pkrvmbietmlfzoi:68247] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd58eaa5a55]
[pkrvmbietmlfzoi:68247] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd58eaa5a6f]
[pkrvmbietmlfzoi:68247] [ 8] plumed_master(+0x146dd)[0x55e3e64146dd]
[pkrvmbietmlfzoi:68247] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd58e62a1ca]
[pkrvmbietmlfzoi:68247] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd58e62a28b]
[pkrvmbietmlfzoi:68247] [11] plumed_master(+0x15365)[0x55e3e6415365]
[pkrvmbietmlfzoi:68247] *** End of error message ***
</pre>
{% endraw %}
