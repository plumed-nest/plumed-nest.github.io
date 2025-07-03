**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test13_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[pkrvmbietmlfzoi:07713] *** Process received signal ***
[pkrvmbietmlfzoi:07713] Signal: Aborted (6)
[pkrvmbietmlfzoi:07713] Signal code:  (-6)
[pkrvmbietmlfzoi:07713] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7efd58645330]
[pkrvmbietmlfzoi:07713] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7efd5869eb2c]
[pkrvmbietmlfzoi:07713] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7efd5864527e]
[pkrvmbietmlfzoi:07713] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7efd586288ff]
[pkrvmbietmlfzoi:07713] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7efd58aa5ff5]
[pkrvmbietmlfzoi:07713] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7efd58abb0da]
[pkrvmbietmlfzoi:07713] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7efd58aa5a55]
[pkrvmbietmlfzoi:07713] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7efd58aa5a6f]
[pkrvmbietmlfzoi:07713] [ 8] plumed(+0x146dd)[0x564c038896dd]
[pkrvmbietmlfzoi:07713] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7efd5862a1ca]
[pkrvmbietmlfzoi:07713] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7efd5862a28b]
[pkrvmbietmlfzoi:07713] [11] plumed(+0x15365)[0x564c0388a365]
[pkrvmbietmlfzoi:07713] *** End of error message ***
</pre>
{% endraw %}
