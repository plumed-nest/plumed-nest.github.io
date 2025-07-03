**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test11_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[pkrvmbietmlfzoi:07610] *** Process received signal ***
[pkrvmbietmlfzoi:07610] Signal: Aborted (6)
[pkrvmbietmlfzoi:07610] Signal code:  (-6)
[pkrvmbietmlfzoi:07610] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa364445330]
[pkrvmbietmlfzoi:07610] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa36449eb2c]
[pkrvmbietmlfzoi:07610] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa36444527e]
[pkrvmbietmlfzoi:07610] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa3644288ff]
[pkrvmbietmlfzoi:07610] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa3648a5ff5]
[pkrvmbietmlfzoi:07610] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa3648bb0da]
[pkrvmbietmlfzoi:07610] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa3648a5a55]
[pkrvmbietmlfzoi:07610] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa3648a5a6f]
[pkrvmbietmlfzoi:07610] [ 8] plumed(+0x146dd)[0x5572ef5206dd]
[pkrvmbietmlfzoi:07610] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa36442a1ca]
[pkrvmbietmlfzoi:07610] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa36442a28b]
[pkrvmbietmlfzoi:07610] [11] plumed(+0x15365)[0x5572ef521365]
[pkrvmbietmlfzoi:07610] *** End of error message ***
</pre>
{% endraw %}
