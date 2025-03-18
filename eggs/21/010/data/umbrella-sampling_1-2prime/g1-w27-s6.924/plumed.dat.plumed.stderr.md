**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w27-s6.924/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az790-36:67115] *** Process received signal ***
[fv-az790-36:67115] Signal: Aborted (6)
[fv-az790-36:67115] Signal code:  (-6)
[fv-az790-36:67115] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7698445330]
[fv-az790-36:67115] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f769849eb2c]
[fv-az790-36:67115] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f769844527e]
[fv-az790-36:67115] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f76984288ff]
[fv-az790-36:67115] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f76988a5ff5]
[fv-az790-36:67115] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f76988bb0da]
[fv-az790-36:67115] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f76988a5a55]
[fv-az790-36:67115] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f76988a5a6f]
[fv-az790-36:67115] [ 8] plumed(+0x146dd)[0x55e93947b6dd]
[fv-az790-36:67115] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f769842a1ca]
[fv-az790-36:67115] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f769842a28b]
[fv-az790-36:67115] [11] plumed(+0x15365)[0x55e93947c365]
[fv-az790-36:67115] *** End of error message ***
</pre>
{% endraw %}
