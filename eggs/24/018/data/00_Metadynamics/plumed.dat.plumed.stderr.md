**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[pkrvmbietmlfzoi:07870] *** Process received signal ***
[pkrvmbietmlfzoi:07870] Signal: Aborted (6)
[pkrvmbietmlfzoi:07870] Signal code:  (-6)
[pkrvmbietmlfzoi:07870] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9a78845330]
[pkrvmbietmlfzoi:07870] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9a7889eb2c]
[pkrvmbietmlfzoi:07870] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9a7884527e]
[pkrvmbietmlfzoi:07870] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9a788288ff]
[pkrvmbietmlfzoi:07870] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9a78ca5ff5]
[pkrvmbietmlfzoi:07870] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9a78cbb0da]
[pkrvmbietmlfzoi:07870] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9a78ca5a55]
[pkrvmbietmlfzoi:07870] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9a78ca5a6f]
[pkrvmbietmlfzoi:07870] [ 8] plumed(+0x146dd)[0x5627afa7b6dd]
[pkrvmbietmlfzoi:07870] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9a7882a1ca]
[pkrvmbietmlfzoi:07870] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9a7882a28b]
[pkrvmbietmlfzoi:07870] [11] plumed(+0x15365)[0x5627afa7c365]
[pkrvmbietmlfzoi:07870] *** End of error message ***
</pre>
{% endraw %}
