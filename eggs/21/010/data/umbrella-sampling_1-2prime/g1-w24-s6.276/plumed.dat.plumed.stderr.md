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
[fv-az789-879:67644] *** Process received signal ***
[fv-az789-879:67644] Signal: Aborted (6)
[fv-az789-879:67644] Signal code:  (-6)
[fv-az789-879:67644] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc6ac445330]
[fv-az789-879:67644] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc6ac49eb2c]
[fv-az789-879:67644] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc6ac44527e]
[fv-az789-879:67644] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc6ac4288ff]
[fv-az789-879:67644] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc6ac8a5ff5]
[fv-az789-879:67644] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc6ac8bb0da]
[fv-az789-879:67644] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc6ac8a5a55]
[fv-az789-879:67644] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc6ac8a5a6f]
[fv-az789-879:67644] [ 8] plumed(+0x146dd)[0x55bc50c046dd]
[fv-az789-879:67644] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc6ac42a1ca]
[fv-az789-879:67644] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc6ac42a28b]
[fv-az789-879:67644] [11] plumed(+0x15365)[0x55bc50c05365]
[fv-az789-879:67644] *** End of error message ***
</pre>
{% endraw %}
