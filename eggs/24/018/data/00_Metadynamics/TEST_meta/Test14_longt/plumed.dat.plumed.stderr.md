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
[pkrvmbietmlfzoi:07764] *** Process received signal ***
[pkrvmbietmlfzoi:07764] Signal: Aborted (6)
[pkrvmbietmlfzoi:07764] Signal code:  (-6)
[pkrvmbietmlfzoi:07764] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbb3da45330]
[pkrvmbietmlfzoi:07764] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbb3da9eb2c]
[pkrvmbietmlfzoi:07764] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbb3da4527e]
[pkrvmbietmlfzoi:07764] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbb3da288ff]
[pkrvmbietmlfzoi:07764] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbb3dea5ff5]
[pkrvmbietmlfzoi:07764] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbb3debb0da]
[pkrvmbietmlfzoi:07764] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbb3dea5a55]
[pkrvmbietmlfzoi:07764] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbb3dea5a6f]
[pkrvmbietmlfzoi:07764] [ 8] plumed(+0x146dd)[0x55824ffdc6dd]
[pkrvmbietmlfzoi:07764] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbb3da2a1ca]
[pkrvmbietmlfzoi:07764] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbb3da2a28b]
[pkrvmbietmlfzoi:07764] [11] plumed(+0x15365)[0x55824ffdd365]
[pkrvmbietmlfzoi:07764] *** End of error message ***
</pre>
{% endraw %}
