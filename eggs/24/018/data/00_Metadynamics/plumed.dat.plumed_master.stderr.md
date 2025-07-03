**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[pkrvmbietmlfzoi:07886] *** Process received signal ***
[pkrvmbietmlfzoi:07886] Signal: Aborted (6)
[pkrvmbietmlfzoi:07886] Signal code:  (-6)
[pkrvmbietmlfzoi:07886] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff0cc445330]
[pkrvmbietmlfzoi:07886] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff0cc49eb2c]
[pkrvmbietmlfzoi:07886] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff0cc44527e]
[pkrvmbietmlfzoi:07886] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff0cc4288ff]
[pkrvmbietmlfzoi:07886] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff0cc8a5ff5]
[pkrvmbietmlfzoi:07886] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff0cc8bb0da]
[pkrvmbietmlfzoi:07886] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff0cc8a5a55]
[pkrvmbietmlfzoi:07886] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff0cc8a5a6f]
[pkrvmbietmlfzoi:07886] [ 8] plumed_master(+0x146dd)[0x55e3fc4696dd]
[pkrvmbietmlfzoi:07886] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff0cc42a1ca]
[pkrvmbietmlfzoi:07886] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff0cc42a28b]
[pkrvmbietmlfzoi:07886] [11] plumed_master(+0x15365)[0x55e3fc46a365]
[pkrvmbietmlfzoi:07886] *** End of error message ***
</pre>
{% endraw %}
