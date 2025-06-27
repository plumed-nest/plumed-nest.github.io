**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test14_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[pkrvmbietmlfzoi:64009] *** Process received signal ***
[pkrvmbietmlfzoi:64009] Signal: Aborted (6)
[pkrvmbietmlfzoi:64009] Signal code:  (-6)
[pkrvmbietmlfzoi:64009] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f505be45330]
[pkrvmbietmlfzoi:64009] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f505be9eb2c]
[pkrvmbietmlfzoi:64009] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f505be4527e]
[pkrvmbietmlfzoi:64009] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f505be288ff]
[pkrvmbietmlfzoi:64009] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f505c2a5ff5]
[pkrvmbietmlfzoi:64009] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f505c2bb0da]
[pkrvmbietmlfzoi:64009] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f505c2a5a55]
[pkrvmbietmlfzoi:64009] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f505c2a5a6f]
[pkrvmbietmlfzoi:64009] [ 8] plumed_master(+0x146dd)[0x5603abc616dd]
[pkrvmbietmlfzoi:64009] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f505be2a1ca]
[pkrvmbietmlfzoi:64009] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f505be2a28b]
[pkrvmbietmlfzoi:64009] [11] plumed_master(+0x15365)[0x5603abc62365]
[pkrvmbietmlfzoi:64009] *** End of error message ***
</pre>
{% endraw %}
