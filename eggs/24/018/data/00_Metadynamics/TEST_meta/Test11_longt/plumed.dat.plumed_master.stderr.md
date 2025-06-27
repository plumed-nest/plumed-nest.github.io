**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test11_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[pkrvmbietmlfzoi:63853] *** Process received signal ***
[pkrvmbietmlfzoi:63853] Signal: Aborted (6)
[pkrvmbietmlfzoi:63853] Signal code:  (-6)
[pkrvmbietmlfzoi:63853] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f96da045330]
[pkrvmbietmlfzoi:63853] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f96da09eb2c]
[pkrvmbietmlfzoi:63853] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f96da04527e]
[pkrvmbietmlfzoi:63853] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f96da0288ff]
[pkrvmbietmlfzoi:63853] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f96da4a5ff5]
[pkrvmbietmlfzoi:63853] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f96da4bb0da]
[pkrvmbietmlfzoi:63853] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f96da4a5a55]
[pkrvmbietmlfzoi:63853] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f96da4a5a6f]
[pkrvmbietmlfzoi:63853] [ 8] plumed_master(+0x146dd)[0x55e1697d76dd]
[pkrvmbietmlfzoi:63853] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f96da02a1ca]
[pkrvmbietmlfzoi:63853] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f96da02a28b]
[pkrvmbietmlfzoi:63853] [11] plumed_master(+0x15365)[0x55e1697d8365]
[pkrvmbietmlfzoi:63853] *** End of error message ***
</pre>
{% endraw %}
