**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w23-s6.060/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az789-879:67609] *** Process received signal ***
[fv-az789-879:67609] Signal: Aborted (6)
[fv-az789-879:67609] Signal code:  (-6)
[fv-az789-879:67609] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7feb8cc45330]
[fv-az789-879:67609] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7feb8cc9eb2c]
[fv-az789-879:67609] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7feb8cc4527e]
[fv-az789-879:67609] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7feb8cc288ff]
[fv-az789-879:67609] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7feb8d0a5ff5]
[fv-az789-879:67609] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7feb8d0bb0da]
[fv-az789-879:67609] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7feb8d0a5a55]
[fv-az789-879:67609] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7feb8d0a5a6f]
[fv-az789-879:67609] [ 8] plumed_master(+0x146dd)[0x56472a4976dd]
[fv-az789-879:67609] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7feb8cc2a1ca]
[fv-az789-879:67609] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7feb8cc2a28b]
[fv-az789-879:67609] [11] plumed_master(+0x15365)[0x56472a498365]
[fv-az789-879:67609] *** End of error message ***
</pre>
{% endraw %}
