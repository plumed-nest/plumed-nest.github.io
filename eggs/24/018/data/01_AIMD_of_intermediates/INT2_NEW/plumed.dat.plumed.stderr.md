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
[pkrvmbietmlfzoi:64513] *** Process received signal ***
[pkrvmbietmlfzoi:64513] Signal: Aborted (6)
[pkrvmbietmlfzoi:64513] Signal code:  (-6)
[pkrvmbietmlfzoi:64513] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd825c45330]
[pkrvmbietmlfzoi:64513] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd825c9eb2c]
[pkrvmbietmlfzoi:64513] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd825c4527e]
[pkrvmbietmlfzoi:64513] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd825c288ff]
[pkrvmbietmlfzoi:64513] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd8260a5ff5]
[pkrvmbietmlfzoi:64513] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd8260bb0da]
[pkrvmbietmlfzoi:64513] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd8260a5a55]
[pkrvmbietmlfzoi:64513] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd8260a5a6f]
[pkrvmbietmlfzoi:64513] [ 8] plumed(+0x146dd)[0x5616278e26dd]
[pkrvmbietmlfzoi:64513] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd825c2a1ca]
[pkrvmbietmlfzoi:64513] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd825c2a28b]
[pkrvmbietmlfzoi:64513] [11] plumed(+0x15365)[0x5616278e3365]
[pkrvmbietmlfzoi:64513] *** End of error message ***
</pre>
{% endraw %}
