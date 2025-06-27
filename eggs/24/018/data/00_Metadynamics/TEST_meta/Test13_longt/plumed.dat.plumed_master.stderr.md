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
[pkrvmbietmlfzoi:63957] *** Process received signal ***
[pkrvmbietmlfzoi:63957] Signal: Aborted (6)
[pkrvmbietmlfzoi:63957] Signal code:  (-6)
[pkrvmbietmlfzoi:63957] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6ba1245330]
[pkrvmbietmlfzoi:63957] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6ba129eb2c]
[pkrvmbietmlfzoi:63957] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6ba124527e]
[pkrvmbietmlfzoi:63957] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6ba12288ff]
[pkrvmbietmlfzoi:63957] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6ba16a5ff5]
[pkrvmbietmlfzoi:63957] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6ba16bb0da]
[pkrvmbietmlfzoi:63957] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6ba16a5a55]
[pkrvmbietmlfzoi:63957] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6ba16a5a6f]
[pkrvmbietmlfzoi:63957] [ 8] plumed_master(+0x146dd)[0x556ce5ad56dd]
[pkrvmbietmlfzoi:63957] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6ba122a1ca]
[pkrvmbietmlfzoi:63957] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6ba122a28b]
[pkrvmbietmlfzoi:63957] [11] plumed_master(+0x15365)[0x556ce5ad6365]
[pkrvmbietmlfzoi:63957] *** End of error message ***
</pre>
{% endraw %}
