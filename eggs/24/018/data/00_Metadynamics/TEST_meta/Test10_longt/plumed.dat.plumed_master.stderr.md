**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test10_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[pkrvmbietmlfzoi:63801] *** Process received signal ***
[pkrvmbietmlfzoi:63801] Signal: Aborted (6)
[pkrvmbietmlfzoi:63801] Signal code:  (-6)
[pkrvmbietmlfzoi:63801] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4c11445330]
[pkrvmbietmlfzoi:63801] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4c1149eb2c]
[pkrvmbietmlfzoi:63801] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4c1144527e]
[pkrvmbietmlfzoi:63801] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4c114288ff]
[pkrvmbietmlfzoi:63801] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4c118a5ff5]
[pkrvmbietmlfzoi:63801] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4c118bb0da]
[pkrvmbietmlfzoi:63801] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4c118a5a55]
[pkrvmbietmlfzoi:63801] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4c118a5a6f]
[pkrvmbietmlfzoi:63801] [ 8] plumed_master(+0x146dd)[0x55c1171e56dd]
[pkrvmbietmlfzoi:63801] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4c1142a1ca]
[pkrvmbietmlfzoi:63801] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4c1142a28b]
[pkrvmbietmlfzoi:63801] [11] plumed_master(+0x15365)[0x55c1171e6365]
[pkrvmbietmlfzoi:63801] *** End of error message ***
</pre>
{% endraw %}
