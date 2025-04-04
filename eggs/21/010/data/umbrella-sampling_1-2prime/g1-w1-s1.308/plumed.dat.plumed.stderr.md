**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w1-s1.308/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az1719-476:10415] *** Process received signal ***
[fv-az1719-476:10415] Signal: Aborted (6)
[fv-az1719-476:10415] Signal code:  (-6)
[fv-az1719-476:10415] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6317045330]
[fv-az1719-476:10415] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f631709eb2c]
[fv-az1719-476:10415] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f631704527e]
[fv-az1719-476:10415] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f63170288ff]
[fv-az1719-476:10415] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f63174a5ff5]
[fv-az1719-476:10415] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f63174bb0da]
[fv-az1719-476:10415] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f63174a5a55]
[fv-az1719-476:10415] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f63174a5a6f]
[fv-az1719-476:10415] [ 8] plumed(+0x146dd)[0x5578a05946dd]
[fv-az1719-476:10415] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f631702a1ca]
[fv-az1719-476:10415] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f631702a28b]
[fv-az1719-476:10415] [11] plumed(+0x15365)[0x5578a0595365]
[fv-az1719-476:10415] *** End of error message ***
</pre>
{% endraw %}
