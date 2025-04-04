**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w26-s6.708/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az1719-476:11344] *** Process received signal ***
[fv-az1719-476:11344] Signal: Aborted (6)
[fv-az1719-476:11344] Signal code:  (-6)
[fv-az1719-476:11344] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd02a645330]
[fv-az1719-476:11344] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd02a69eb2c]
[fv-az1719-476:11344] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd02a64527e]
[fv-az1719-476:11344] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd02a6288ff]
[fv-az1719-476:11344] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd02aaa5ff5]
[fv-az1719-476:11344] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd02aabb0da]
[fv-az1719-476:11344] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd02aaa5a55]
[fv-az1719-476:11344] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd02aaa5a6f]
[fv-az1719-476:11344] [ 8] plumed(+0x146dd)[0x55e6ed4176dd]
[fv-az1719-476:11344] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd02a62a1ca]
[fv-az1719-476:11344] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd02a62a28b]
[fv-az1719-476:11344] [11] plumed(+0x15365)[0x55e6ed418365]
[fv-az1719-476:11344] *** End of error message ***
</pre>
{% endraw %}
