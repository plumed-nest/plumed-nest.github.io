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
[fv-az789-879:67746] *** Process received signal ***
[fv-az789-879:67746] Signal: Aborted (6)
[fv-az789-879:67746] Signal code:  (-6)
[fv-az789-879:67746] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f726c845330]
[fv-az789-879:67746] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f726c89eb2c]
[fv-az789-879:67746] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f726c84527e]
[fv-az789-879:67746] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f726c8288ff]
[fv-az789-879:67746] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f726cca5ff5]
[fv-az789-879:67746] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f726ccbb0da]
[fv-az789-879:67746] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f726cca5a55]
[fv-az789-879:67746] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f726cca5a6f]
[fv-az789-879:67746] [ 8] plumed(+0x146dd)[0x55f4cc30c6dd]
[fv-az789-879:67746] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f726c82a1ca]
[fv-az789-879:67746] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f726c82a28b]
[fv-az789-879:67746] [11] plumed(+0x15365)[0x55f4cc30d365]
[fv-az789-879:67746] *** End of error message ***
</pre>
{% endraw %}
