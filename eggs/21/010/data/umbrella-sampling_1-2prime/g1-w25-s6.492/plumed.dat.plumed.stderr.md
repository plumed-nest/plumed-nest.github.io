**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w25-s6.492/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az787-589:65416] *** Process received signal ***
[fv-az787-589:65416] Signal: Aborted (6)
[fv-az787-589:65416] Signal code:  (-6)
[fv-az787-589:65416] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f001ba45330]
[fv-az787-589:65416] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f001ba9eb2c]
[fv-az787-589:65416] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f001ba4527e]
[fv-az787-589:65416] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f001ba288ff]
[fv-az787-589:65416] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f001bea5ff5]
[fv-az787-589:65416] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f001bebb0da]
[fv-az787-589:65416] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f001bea5a55]
[fv-az787-589:65416] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f001bea5a6f]
[fv-az787-589:65416] [ 8] plumed(+0x146dd)[0x5578d1cbd6dd]
[fv-az787-589:65416] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f001ba2a1ca]
[fv-az787-589:65416] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f001ba2a28b]
[fv-az787-589:65416] [11] plumed(+0x15365)[0x5578d1cbe365]
[fv-az787-589:65416] *** End of error message ***
</pre>
{% endraw %}
