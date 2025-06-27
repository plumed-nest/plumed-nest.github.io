**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-2/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[pkrvmbietmlfzoi:68091] *** Process received signal ***
[pkrvmbietmlfzoi:68091] Signal: Aborted (6)
[pkrvmbietmlfzoi:68091] Signal code:  (-6)
[pkrvmbietmlfzoi:68091] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3d40645330]
[pkrvmbietmlfzoi:68091] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3d4069eb2c]
[pkrvmbietmlfzoi:68091] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3d4064527e]
[pkrvmbietmlfzoi:68091] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3d406288ff]
[pkrvmbietmlfzoi:68091] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3d40aa5ff5]
[pkrvmbietmlfzoi:68091] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3d40abb0da]
[pkrvmbietmlfzoi:68091] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3d40aa5a55]
[pkrvmbietmlfzoi:68091] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3d40aa5a6f]
[pkrvmbietmlfzoi:68091] [ 8] plumed_master(+0x146dd)[0x55ca9cc946dd]
[pkrvmbietmlfzoi:68091] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3d4062a1ca]
[pkrvmbietmlfzoi:68091] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3d4062a28b]
[pkrvmbietmlfzoi:68091] [11] plumed_master(+0x15365)[0x55ca9cc95365]
[pkrvmbietmlfzoi:68091] *** End of error message ***
</pre>
{% endraw %}
