**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  01_AIMD_of_intermediates/INT2_NEW/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[pkrvmbietmlfzoi:08282] *** Process received signal ***
[pkrvmbietmlfzoi:08282] Signal: Aborted (6)
[pkrvmbietmlfzoi:08282] Signal code:  (-6)
[pkrvmbietmlfzoi:08282] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3f96245330]
[pkrvmbietmlfzoi:08282] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3f9629eb2c]
[pkrvmbietmlfzoi:08282] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3f9624527e]
[pkrvmbietmlfzoi:08282] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3f962288ff]
[pkrvmbietmlfzoi:08282] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3f966a5ff5]
[pkrvmbietmlfzoi:08282] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3f966bb0da]
[pkrvmbietmlfzoi:08282] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3f966a5a55]
[pkrvmbietmlfzoi:08282] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3f966a5a6f]
[pkrvmbietmlfzoi:08282] [ 8] plumed(+0x146dd)[0x562994ccd6dd]
[pkrvmbietmlfzoi:08282] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3f9622a1ca]
[pkrvmbietmlfzoi:08282] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3f9622a28b]
[pkrvmbietmlfzoi:08282] [11] plumed(+0x15365)[0x562994cce365]
[pkrvmbietmlfzoi:08282] *** End of error message ***
</pre>
{% endraw %}
