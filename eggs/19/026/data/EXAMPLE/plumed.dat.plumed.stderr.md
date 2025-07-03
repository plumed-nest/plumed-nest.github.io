**Project ID:** [plumID:19.026]({{ '/' | absolute_url }}eggs/19/026/)  
Stderr for source:  EXAMPLE/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HBOND_COORD" is not known.
[pkrvmbietmlfzoi:14075] *** Process received signal ***
[pkrvmbietmlfzoi:14075] Signal: Aborted (6)
[pkrvmbietmlfzoi:14075] Signal code:  (-6)
[pkrvmbietmlfzoi:14075] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2dfac45330]
[pkrvmbietmlfzoi:14075] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2dfac9eb2c]
[pkrvmbietmlfzoi:14075] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2dfac4527e]
[pkrvmbietmlfzoi:14075] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2dfac288ff]
[pkrvmbietmlfzoi:14075] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2dfb0a5ff5]
[pkrvmbietmlfzoi:14075] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2dfb0bb0da]
[pkrvmbietmlfzoi:14075] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2dfb0a5a55]
[pkrvmbietmlfzoi:14075] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2dfb0a5a6f]
[pkrvmbietmlfzoi:14075] [ 8] plumed(+0x146dd)[0x55ef7de9f6dd]
[pkrvmbietmlfzoi:14075] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2dfac2a1ca]
[pkrvmbietmlfzoi:14075] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2dfac2a28b]
[pkrvmbietmlfzoi:14075] [11] plumed(+0x15365)[0x55ef7dea0365]
[pkrvmbietmlfzoi:14075] *** End of error message ***
</pre>
{% endraw %}
