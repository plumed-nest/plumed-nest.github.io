**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w26-s6.708/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az1719-476:11360] *** Process received signal ***
[fv-az1719-476:11360] Signal: Aborted (6)
[fv-az1719-476:11360] Signal code:  (-6)
[fv-az1719-476:11360] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fead7245330]
[fv-az1719-476:11360] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fead729eb2c]
[fv-az1719-476:11360] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fead724527e]
[fv-az1719-476:11360] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fead72288ff]
[fv-az1719-476:11360] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fead76a5ff5]
[fv-az1719-476:11360] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fead76bb0da]
[fv-az1719-476:11360] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fead76a5a55]
[fv-az1719-476:11360] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fead76a5a6f]
[fv-az1719-476:11360] [ 8] plumed_master(+0x146dd)[0x5574eb82f6dd]
[fv-az1719-476:11360] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fead722a1ca]
[fv-az1719-476:11360] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fead722a28b]
[fv-az1719-476:11360] [11] plumed_master(+0x15365)[0x5574eb830365]
[fv-az1719-476:11360] *** End of error message ***
</pre>
{% endraw %}
