**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test14_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[pkrvmbietmlfzoi:63993] *** Process received signal ***
[pkrvmbietmlfzoi:63993] Signal: Aborted (6)
[pkrvmbietmlfzoi:63993] Signal code:  (-6)
[pkrvmbietmlfzoi:63993] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff6d6445330]
[pkrvmbietmlfzoi:63993] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff6d649eb2c]
[pkrvmbietmlfzoi:63993] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff6d644527e]
[pkrvmbietmlfzoi:63993] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff6d64288ff]
[pkrvmbietmlfzoi:63993] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff6d68a5ff5]
[pkrvmbietmlfzoi:63993] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff6d68bb0da]
[pkrvmbietmlfzoi:63993] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff6d68a5a55]
[pkrvmbietmlfzoi:63993] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff6d68a5a6f]
[pkrvmbietmlfzoi:63993] [ 8] plumed(+0x146dd)[0x5617f4e3c6dd]
[pkrvmbietmlfzoi:63993] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff6d642a1ca]
[pkrvmbietmlfzoi:63993] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff6d642a28b]
[pkrvmbietmlfzoi:63993] [11] plumed(+0x15365)[0x5617f4e3d365]
[pkrvmbietmlfzoi:63993] *** End of error message ***
</pre>
{% endraw %}
