**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w18-s4.980/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az787-589:65023] *** Process received signal ***
[fv-az787-589:65023] Signal: Aborted (6)
[fv-az787-589:65023] Signal code:  (-6)
[fv-az787-589:65023] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fdbe0045330]
[fv-az787-589:65023] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fdbe009eb2c]
[fv-az787-589:65023] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fdbe004527e]
[fv-az787-589:65023] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fdbe00288ff]
[fv-az787-589:65023] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fdbe04a5ff5]
[fv-az787-589:65023] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fdbe04bb0da]
[fv-az787-589:65023] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fdbe04a5a55]
[fv-az787-589:65023] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fdbe04a5a6f]
[fv-az787-589:65023] [ 8] plumed_master(+0x146dd)[0x55d2770086dd]
[fv-az787-589:65023] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fdbe002a1ca]
[fv-az787-589:65023] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fdbe002a28b]
[fv-az787-589:65023] [11] plumed_master(+0x15365)[0x55d277009365]
[fv-az787-589:65023] *** End of error message ***
</pre>
{% endraw %}
