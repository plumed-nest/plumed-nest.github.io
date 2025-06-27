**Project ID:** [plumID:23.043]({{ '/' | absolute_url }}eggs/23/043/)  
Stderr for source:  metad-example/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "SPHERICAL_EXPANSION" is not known.
[pkrvmbietmlfzoi:64108] *** Process received signal ***
[pkrvmbietmlfzoi:64108] Signal: Aborted (6)
[pkrvmbietmlfzoi:64108] Signal code:  (-6)
[pkrvmbietmlfzoi:64108] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4628845330]
[pkrvmbietmlfzoi:64108] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f462889eb2c]
[pkrvmbietmlfzoi:64108] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f462884527e]
[pkrvmbietmlfzoi:64108] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f46288288ff]
[pkrvmbietmlfzoi:64108] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4628ca5ff5]
[pkrvmbietmlfzoi:64108] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4628cbb0da]
[pkrvmbietmlfzoi:64108] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4628ca5a55]
[pkrvmbietmlfzoi:64108] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4628ca5a6f]
[pkrvmbietmlfzoi:64108] [ 8] plumed_master(+0x146dd)[0x563003b106dd]
[pkrvmbietmlfzoi:64108] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f462882a1ca]
[pkrvmbietmlfzoi:64108] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f462882a28b]
[pkrvmbietmlfzoi:64108] [11] plumed_master(+0x15365)[0x563003b11365]
[pkrvmbietmlfzoi:64108] *** End of error message ***
</pre>
{% endraw %}
