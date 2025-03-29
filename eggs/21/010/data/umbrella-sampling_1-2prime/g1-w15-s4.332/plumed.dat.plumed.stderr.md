**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w15-s4.332/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az789-879:67130] *** Process received signal ***
[fv-az789-879:67130] Signal: Aborted (6)
[fv-az789-879:67130] Signal code:  (-6)
[fv-az789-879:67130] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f91a3e45330]
[fv-az789-879:67130] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f91a3e9eb2c]
[fv-az789-879:67130] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f91a3e4527e]
[fv-az789-879:67130] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f91a3e288ff]
[fv-az789-879:67130] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f91a42a5ff5]
[fv-az789-879:67130] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f91a42bb0da]
[fv-az789-879:67130] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f91a42a5a55]
[fv-az789-879:67130] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f91a42a5a6f]
[fv-az789-879:67130] [ 8] plumed(+0x146dd)[0x5639bfe1f6dd]
[fv-az789-879:67130] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f91a3e2a1ca]
[fv-az789-879:67130] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f91a3e2a28b]
[fv-az789-879:67130] [11] plumed(+0x15365)[0x5639bfe20365]
[fv-az789-879:67130] *** End of error message ***
</pre>
{% endraw %}
