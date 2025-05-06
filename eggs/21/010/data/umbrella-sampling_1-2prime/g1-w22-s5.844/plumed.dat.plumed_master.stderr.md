**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w22-s5.844/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az2209-645:65847] *** Process received signal ***
[fv-az2209-645:65847] Signal: Aborted (6)
[fv-az2209-645:65847] Signal code:  (-6)
[fv-az2209-645:65847] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe040a45330]
[fv-az2209-645:65847] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe040a9eb2c]
[fv-az2209-645:65847] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe040a4527e]
[fv-az2209-645:65847] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe040a288ff]
[fv-az2209-645:65847] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe040ea5ff5]
[fv-az2209-645:65847] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe040ebb0da]
[fv-az2209-645:65847] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe040ea5a55]
[fv-az2209-645:65847] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe040ea5a6f]
[fv-az2209-645:65847] [ 8] plumed_master(+0x146dd)[0x55992a84d6dd]
[fv-az2209-645:65847] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe040a2a1ca]
[fv-az2209-645:65847] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe040a2a28b]
[fv-az2209-645:65847] [11] plumed_master(+0x15365)[0x55992a84e365]
[fv-az2209-645:65847] *** End of error message ***
</pre>
{% endraw %}
