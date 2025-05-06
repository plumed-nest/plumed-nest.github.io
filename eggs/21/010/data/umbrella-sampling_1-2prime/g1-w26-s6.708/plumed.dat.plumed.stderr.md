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
[fv-az2209-645:66038] *** Process received signal ***
[fv-az2209-645:66038] Signal: Aborted (6)
[fv-az2209-645:66038] Signal code:  (-6)
[fv-az2209-645:66038] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4278e45330]
[fv-az2209-645:66038] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4278e9eb2c]
[fv-az2209-645:66038] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4278e4527e]
[fv-az2209-645:66038] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4278e288ff]
[fv-az2209-645:66038] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f42792a5ff5]
[fv-az2209-645:66038] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f42792bb0da]
[fv-az2209-645:66038] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f42792a5a55]
[fv-az2209-645:66038] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f42792a5a6f]
[fv-az2209-645:66038] [ 8] plumed(+0x146dd)[0x55c0711c66dd]
[fv-az2209-645:66038] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4278e2a1ca]
[fv-az2209-645:66038] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4278e2a28b]
[fv-az2209-645:66038] [11] plumed(+0x15365)[0x55c0711c7365]
[fv-az2209-645:66038] *** End of error message ***
</pre>
{% endraw %}
