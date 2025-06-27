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
[pkrvmbietmlfzoi:63889] *** Process received signal ***
[pkrvmbietmlfzoi:63889] Signal: Aborted (6)
[pkrvmbietmlfzoi:63889] Signal code:  (-6)
[pkrvmbietmlfzoi:63889] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8a95245330]
[pkrvmbietmlfzoi:63889] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8a9529eb2c]
[pkrvmbietmlfzoi:63889] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8a9524527e]
[pkrvmbietmlfzoi:63889] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8a952288ff]
[pkrvmbietmlfzoi:63889] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8a956a5ff5]
[pkrvmbietmlfzoi:63889] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8a956bb0da]
[pkrvmbietmlfzoi:63889] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8a956a5a55]
[pkrvmbietmlfzoi:63889] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8a956a5a6f]
[pkrvmbietmlfzoi:63889] [ 8] plumed(+0x146dd)[0x560f6038d6dd]
[pkrvmbietmlfzoi:63889] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8a9522a1ca]
[pkrvmbietmlfzoi:63889] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8a9522a28b]
[pkrvmbietmlfzoi:63889] [11] plumed(+0x15365)[0x560f6038e365]
[pkrvmbietmlfzoi:63889] *** End of error message ***
</pre>
{% endraw %}
