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
[fv-az789-879:67695] *** Process received signal ***
[fv-az789-879:67695] Signal: Aborted (6)
[fv-az789-879:67695] Signal code:  (-6)
[fv-az789-879:67695] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f47dac45330]
[fv-az789-879:67695] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f47dac9eb2c]
[fv-az789-879:67695] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f47dac4527e]
[fv-az789-879:67695] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f47dac288ff]
[fv-az789-879:67695] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f47db0a5ff5]
[fv-az789-879:67695] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f47db0bb0da]
[fv-az789-879:67695] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f47db0a5a55]
[fv-az789-879:67695] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f47db0a5a6f]
[fv-az789-879:67695] [ 8] plumed(+0x146dd)[0x55ab58a736dd]
[fv-az789-879:67695] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f47dac2a1ca]
[fv-az789-879:67695] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f47dac2a28b]
[fv-az789-879:67695] [11] plumed(+0x15365)[0x55ab58a74365]
[fv-az789-879:67695] *** End of error message ***
</pre>
{% endraw %}
