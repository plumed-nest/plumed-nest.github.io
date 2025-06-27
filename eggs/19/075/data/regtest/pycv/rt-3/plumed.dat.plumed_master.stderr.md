**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-3/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[pkrvmbietmlfzoi:68143] *** Process received signal ***
[pkrvmbietmlfzoi:68143] Signal: Aborted (6)
[pkrvmbietmlfzoi:68143] Signal code:  (-6)
[pkrvmbietmlfzoi:68143] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5d45a45330]
[pkrvmbietmlfzoi:68143] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5d45a9eb2c]
[pkrvmbietmlfzoi:68143] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5d45a4527e]
[pkrvmbietmlfzoi:68143] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5d45a288ff]
[pkrvmbietmlfzoi:68143] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5d45ea5ff5]
[pkrvmbietmlfzoi:68143] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5d45ebb0da]
[pkrvmbietmlfzoi:68143] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5d45ea5a55]
[pkrvmbietmlfzoi:68143] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5d45ea5a6f]
[pkrvmbietmlfzoi:68143] [ 8] plumed_master(+0x146dd)[0x56201c19a6dd]
[pkrvmbietmlfzoi:68143] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5d45a2a1ca]
[pkrvmbietmlfzoi:68143] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5d45a2a28b]
[pkrvmbietmlfzoi:68143] [11] plumed_master(+0x15365)[0x56201c19b365]
[pkrvmbietmlfzoi:68143] *** End of error message ***
</pre>
{% endraw %}
