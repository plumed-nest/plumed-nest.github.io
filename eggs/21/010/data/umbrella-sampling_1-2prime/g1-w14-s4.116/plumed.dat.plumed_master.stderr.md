**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w14-s4.116/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az1719-476:10690] *** Process received signal ***
[fv-az1719-476:10690] Signal: Aborted (6)
[fv-az1719-476:10690] Signal code:  (-6)
[fv-az1719-476:10690] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd17f045330]
[fv-az1719-476:10690] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd17f09eb2c]
[fv-az1719-476:10690] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd17f04527e]
[fv-az1719-476:10690] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd17f0288ff]
[fv-az1719-476:10690] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd17f4a5ff5]
[fv-az1719-476:10690] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd17f4bb0da]
[fv-az1719-476:10690] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd17f4a5a55]
[fv-az1719-476:10690] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd17f4a5a6f]
[fv-az1719-476:10690] [ 8] plumed_master(+0x146dd)[0x565517be66dd]
[fv-az1719-476:10690] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd17f02a1ca]
[fv-az1719-476:10690] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd17f02a28b]
[fv-az1719-476:10690] [11] plumed_master(+0x15365)[0x565517be7365]
[fv-az1719-476:10690] *** End of error message ***
</pre>
{% endraw %}
