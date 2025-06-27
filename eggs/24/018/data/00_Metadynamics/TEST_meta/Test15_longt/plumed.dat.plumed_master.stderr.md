**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test15_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[pkrvmbietmlfzoi:64063] *** Process received signal ***
[pkrvmbietmlfzoi:64063] Signal: Aborted (6)
[pkrvmbietmlfzoi:64063] Signal code:  (-6)
[pkrvmbietmlfzoi:64063] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4ffbe45330]
[pkrvmbietmlfzoi:64063] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4ffbe9eb2c]
[pkrvmbietmlfzoi:64063] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4ffbe4527e]
[pkrvmbietmlfzoi:64063] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4ffbe288ff]
[pkrvmbietmlfzoi:64063] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4ffc2a5ff5]
[pkrvmbietmlfzoi:64063] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4ffc2bb0da]
[pkrvmbietmlfzoi:64063] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4ffc2a5a55]
[pkrvmbietmlfzoi:64063] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4ffc2a5a6f]
[pkrvmbietmlfzoi:64063] [ 8] plumed_master(+0x146dd)[0x55f8595a16dd]
[pkrvmbietmlfzoi:64063] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4ffbe2a1ca]
[pkrvmbietmlfzoi:64063] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4ffbe2a28b]
[pkrvmbietmlfzoi:64063] [11] plumed_master(+0x15365)[0x55f8595a2365]
[pkrvmbietmlfzoi:64063] *** End of error message ***
</pre>
{% endraw %}
