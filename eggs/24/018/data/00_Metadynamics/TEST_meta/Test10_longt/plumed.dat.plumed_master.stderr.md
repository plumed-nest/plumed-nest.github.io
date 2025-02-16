**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test10_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az787-589:60802] *** Process received signal ***
[fv-az787-589:60802] Signal: Aborted (6)
[fv-az787-589:60802] Signal code:  (-6)
[fv-az787-589:60802] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fea40445330]
[fv-az787-589:60802] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fea4049eb2c]
[fv-az787-589:60802] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fea4044527e]
[fv-az787-589:60802] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fea404288ff]
[fv-az787-589:60802] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fea408a5ff5]
[fv-az787-589:60802] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fea408bb0da]
[fv-az787-589:60802] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fea408a5a55]
[fv-az787-589:60802] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fea408a5a6f]
[fv-az787-589:60802] [ 8] plumed_master(+0x146dd)[0x5593a0f856dd]
[fv-az787-589:60802] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fea4042a1ca]
[fv-az787-589:60802] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fea4042a28b]
[fv-az787-589:60802] [11] plumed_master(+0x15365)[0x5593a0f86365]
[fv-az787-589:60802] *** End of error message ***
</pre>
{% endraw %}
