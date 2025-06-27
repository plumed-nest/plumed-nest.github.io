**Project ID:** [plumID:19.026]({{ '/' | absolute_url }}eggs/19/026/)  
Stderr for source:  EXAMPLE/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HBOND_COORD" is not known.
[pkrvmbietmlfzoi:69682] *** Process received signal ***
[pkrvmbietmlfzoi:69682] Signal: Aborted (6)
[pkrvmbietmlfzoi:69682] Signal code:  (-6)
[pkrvmbietmlfzoi:69682] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0159845330]
[pkrvmbietmlfzoi:69682] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f015989eb2c]
[pkrvmbietmlfzoi:69682] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f015984527e]
[pkrvmbietmlfzoi:69682] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f01598288ff]
[pkrvmbietmlfzoi:69682] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0159ca5ff5]
[pkrvmbietmlfzoi:69682] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0159cbb0da]
[pkrvmbietmlfzoi:69682] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0159ca5a55]
[pkrvmbietmlfzoi:69682] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0159ca5a6f]
[pkrvmbietmlfzoi:69682] [ 8] plumed_master(+0x146dd)[0x56511b3226dd]
[pkrvmbietmlfzoi:69682] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f015982a1ca]
[pkrvmbietmlfzoi:69682] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f015982a28b]
[pkrvmbietmlfzoi:69682] [11] plumed_master(+0x15365)[0x56511b323365]
[pkrvmbietmlfzoi:69682] *** End of error message ***
</pre>
{% endraw %}
