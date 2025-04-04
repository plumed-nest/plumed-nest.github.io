**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w24-s6.276/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az1719-476:11242] *** Process received signal ***
[fv-az1719-476:11242] Signal: Aborted (6)
[fv-az1719-476:11242] Signal code:  (-6)
[fv-az1719-476:11242] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7643445330]
[fv-az1719-476:11242] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f764349eb2c]
[fv-az1719-476:11242] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f764344527e]
[fv-az1719-476:11242] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f76434288ff]
[fv-az1719-476:11242] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f76438a5ff5]
[fv-az1719-476:11242] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f76438bb0da]
[fv-az1719-476:11242] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f76438a5a55]
[fv-az1719-476:11242] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f76438a5a6f]
[fv-az1719-476:11242] [ 8] plumed(+0x146dd)[0x55e1cfde36dd]
[fv-az1719-476:11242] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f764342a1ca]
[fv-az1719-476:11242] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f764342a28b]
[fv-az1719-476:11242] [11] plumed(+0x15365)[0x55e1cfde4365]
[fv-az1719-476:11242] *** End of error message ***
</pre>
{% endraw %}
