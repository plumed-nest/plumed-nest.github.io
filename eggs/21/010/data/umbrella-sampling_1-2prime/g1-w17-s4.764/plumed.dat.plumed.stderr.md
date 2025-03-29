**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w17-s4.764/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az789-879:67234] *** Process received signal ***
[fv-az789-879:67234] Signal: Aborted (6)
[fv-az789-879:67234] Signal code:  (-6)
[fv-az789-879:67234] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fab57845330]
[fv-az789-879:67234] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fab5789eb2c]
[fv-az789-879:67234] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fab5784527e]
[fv-az789-879:67234] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fab578288ff]
[fv-az789-879:67234] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fab57ca5ff5]
[fv-az789-879:67234] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fab57cbb0da]
[fv-az789-879:67234] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fab57ca5a55]
[fv-az789-879:67234] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fab57ca5a6f]
[fv-az789-879:67234] [ 8] plumed(+0x146dd)[0x55de5cf6c6dd]
[fv-az789-879:67234] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fab5782a1ca]
[fv-az789-879:67234] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fab5782a28b]
[fv-az789-879:67234] [11] plumed(+0x15365)[0x55de5cf6d365]
[fv-az789-879:67234] *** End of error message ***
</pre>
{% endraw %}
