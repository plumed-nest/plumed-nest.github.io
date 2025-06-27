**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  01_AIMD_of_intermediates/INT1_Methanal_and_Cyanide_and_Amoniac/OLD/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[pkrvmbietmlfzoi:64323] *** Process received signal ***
[pkrvmbietmlfzoi:64323] Signal: Aborted (6)
[pkrvmbietmlfzoi:64323] Signal code:  (-6)
[pkrvmbietmlfzoi:64323] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fde14045330]
[pkrvmbietmlfzoi:64323] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fde1409eb2c]
[pkrvmbietmlfzoi:64323] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fde1404527e]
[pkrvmbietmlfzoi:64323] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fde140288ff]
[pkrvmbietmlfzoi:64323] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fde144a5ff5]
[pkrvmbietmlfzoi:64323] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fde144bb0da]
[pkrvmbietmlfzoi:64323] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fde144a5a55]
[pkrvmbietmlfzoi:64323] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fde144a5a6f]
[pkrvmbietmlfzoi:64323] [ 8] plumed_master(+0x146dd)[0x55f54dbdb6dd]
[pkrvmbietmlfzoi:64323] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fde1402a1ca]
[pkrvmbietmlfzoi:64323] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fde1402a28b]
[pkrvmbietmlfzoi:64323] [11] plumed_master(+0x15365)[0x55f54dbdc365]
[pkrvmbietmlfzoi:64323] *** End of error message ***
</pre>
{% endraw %}
