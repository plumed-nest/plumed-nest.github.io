**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test12_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[pkrvmbietmlfzoi:07661] *** Process received signal ***
[pkrvmbietmlfzoi:07661] Signal: Aborted (6)
[pkrvmbietmlfzoi:07661] Signal code:  (-6)
[pkrvmbietmlfzoi:07661] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7feff7645330]
[pkrvmbietmlfzoi:07661] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7feff769eb2c]
[pkrvmbietmlfzoi:07661] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7feff764527e]
[pkrvmbietmlfzoi:07661] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7feff76288ff]
[pkrvmbietmlfzoi:07661] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7feff7aa5ff5]
[pkrvmbietmlfzoi:07661] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7feff7abb0da]
[pkrvmbietmlfzoi:07661] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7feff7aa5a55]
[pkrvmbietmlfzoi:07661] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7feff7aa5a6f]
[pkrvmbietmlfzoi:07661] [ 8] plumed(+0x146dd)[0x55865e4b86dd]
[pkrvmbietmlfzoi:07661] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7feff762a1ca]
[pkrvmbietmlfzoi:07661] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7feff762a28b]
[pkrvmbietmlfzoi:07661] [11] plumed(+0x15365)[0x55865e4b9365]
[pkrvmbietmlfzoi:07661] *** End of error message ***
</pre>
{% endraw %}
