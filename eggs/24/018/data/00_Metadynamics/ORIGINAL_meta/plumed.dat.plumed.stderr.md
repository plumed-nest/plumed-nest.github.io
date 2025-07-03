**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/ORIGINAL_meta/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[pkrvmbietmlfzoi:07501] *** Process received signal ***
[pkrvmbietmlfzoi:07501] Signal: Aborted (6)
[pkrvmbietmlfzoi:07501] Signal code:  (-6)
[pkrvmbietmlfzoi:07501] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fee12445330]
[pkrvmbietmlfzoi:07501] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fee1249eb2c]
[pkrvmbietmlfzoi:07501] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fee1244527e]
[pkrvmbietmlfzoi:07501] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fee124288ff]
[pkrvmbietmlfzoi:07501] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fee128a5ff5]
[pkrvmbietmlfzoi:07501] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fee128bb0da]
[pkrvmbietmlfzoi:07501] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fee128a5a55]
[pkrvmbietmlfzoi:07501] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fee128a5a6f]
[pkrvmbietmlfzoi:07501] [ 8] plumed(+0x146dd)[0x5596e16726dd]
[pkrvmbietmlfzoi:07501] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fee1242a1ca]
[pkrvmbietmlfzoi:07501] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fee1242a28b]
[pkrvmbietmlfzoi:07501] [11] plumed(+0x15365)[0x5596e1673365]
[pkrvmbietmlfzoi:07501] *** End of error message ***
</pre>
{% endraw %}
