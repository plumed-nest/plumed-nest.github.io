**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-multi-1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[pkrvmbietmlfzoi:68435] *** Process received signal ***
[pkrvmbietmlfzoi:68435] Signal: Aborted (6)
[pkrvmbietmlfzoi:68435] Signal code:  (-6)
[pkrvmbietmlfzoi:68435] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1da8c45330]
[pkrvmbietmlfzoi:68435] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1da8c9eb2c]
[pkrvmbietmlfzoi:68435] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1da8c4527e]
[pkrvmbietmlfzoi:68435] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1da8c288ff]
[pkrvmbietmlfzoi:68435] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1da90a5ff5]
[pkrvmbietmlfzoi:68435] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1da90bb0da]
[pkrvmbietmlfzoi:68435] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1da90a5a55]
[pkrvmbietmlfzoi:68435] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1da90a5a6f]
[pkrvmbietmlfzoi:68435] [ 8] plumed(+0x146dd)[0x55d2346096dd]
[pkrvmbietmlfzoi:68435] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1da8c2a1ca]
[pkrvmbietmlfzoi:68435] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1da8c2a28b]
[pkrvmbietmlfzoi:68435] [11] plumed(+0x15365)[0x55d23460a365]
[pkrvmbietmlfzoi:68435] *** End of error message ***
</pre>
{% endraw %}
