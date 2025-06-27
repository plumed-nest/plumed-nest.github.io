**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test10_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[pkrvmbietmlfzoi:63785] *** Process received signal ***
[pkrvmbietmlfzoi:63785] Signal: Aborted (6)
[pkrvmbietmlfzoi:63785] Signal code:  (-6)
[pkrvmbietmlfzoi:63785] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa154c45330]
[pkrvmbietmlfzoi:63785] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa154c9eb2c]
[pkrvmbietmlfzoi:63785] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa154c4527e]
[pkrvmbietmlfzoi:63785] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa154c288ff]
[pkrvmbietmlfzoi:63785] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa1550a5ff5]
[pkrvmbietmlfzoi:63785] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa1550bb0da]
[pkrvmbietmlfzoi:63785] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa1550a5a55]
[pkrvmbietmlfzoi:63785] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa1550a5a6f]
[pkrvmbietmlfzoi:63785] [ 8] plumed(+0x146dd)[0x55a00b0096dd]
[pkrvmbietmlfzoi:63785] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa154c2a1ca]
[pkrvmbietmlfzoi:63785] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa154c2a28b]
[pkrvmbietmlfzoi:63785] [11] plumed(+0x15365)[0x55a00b00a365]
[pkrvmbietmlfzoi:63785] *** End of error message ***
</pre>
{% endraw %}
