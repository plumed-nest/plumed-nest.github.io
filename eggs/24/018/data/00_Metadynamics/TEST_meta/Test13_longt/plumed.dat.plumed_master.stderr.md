**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test13_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[pkrvmbietmlfzoi:07729] *** Process received signal ***
[pkrvmbietmlfzoi:07729] Signal: Aborted (6)
[pkrvmbietmlfzoi:07729] Signal code:  (-6)
[pkrvmbietmlfzoi:07729] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe577445330]
[pkrvmbietmlfzoi:07729] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe57749eb2c]
[pkrvmbietmlfzoi:07729] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe57744527e]
[pkrvmbietmlfzoi:07729] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe5774288ff]
[pkrvmbietmlfzoi:07729] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe5778a5ff5]
[pkrvmbietmlfzoi:07729] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe5778bb0da]
[pkrvmbietmlfzoi:07729] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe5778a5a55]
[pkrvmbietmlfzoi:07729] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe5778a5a6f]
[pkrvmbietmlfzoi:07729] [ 8] plumed_master(+0x146dd)[0x5576ac5736dd]
[pkrvmbietmlfzoi:07729] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe57742a1ca]
[pkrvmbietmlfzoi:07729] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe57742a28b]
[pkrvmbietmlfzoi:07729] [11] plumed_master(+0x15365)[0x5576ac574365]
[pkrvmbietmlfzoi:07729] *** End of error message ***
</pre>
{% endraw %}
