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
[pkrvmbietmlfzoi:09410] *** Process received signal ***
[pkrvmbietmlfzoi:09410] Signal: Aborted (6)
[pkrvmbietmlfzoi:09410] Signal code:  (-6)
[pkrvmbietmlfzoi:09410] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5704045330]
[pkrvmbietmlfzoi:09410] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f570409eb2c]
[pkrvmbietmlfzoi:09410] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f570404527e]
[pkrvmbietmlfzoi:09410] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f57040288ff]
[pkrvmbietmlfzoi:09410] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f57044a5ff5]
[pkrvmbietmlfzoi:09410] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f57044bb0da]
[pkrvmbietmlfzoi:09410] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f57044a5a55]
[pkrvmbietmlfzoi:09410] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f57044a5a6f]
[pkrvmbietmlfzoi:09410] [ 8] plumed_master(+0x146dd)[0x55596d17f6dd]
[pkrvmbietmlfzoi:09410] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f570402a1ca]
[pkrvmbietmlfzoi:09410] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f570402a28b]
[pkrvmbietmlfzoi:09410] [11] plumed_master(+0x15365)[0x55596d180365]
[pkrvmbietmlfzoi:09410] *** End of error message ***
</pre>
{% endraw %}
