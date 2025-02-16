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
[fv-az787-589:65520] *** Process received signal ***
[fv-az787-589:65520] Signal: Aborted (6)
[fv-az787-589:65520] Signal code:  (-6)
[fv-az787-589:65520] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0e45045330]
[fv-az787-589:65520] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0e4509eb2c]
[fv-az787-589:65520] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0e4504527e]
[fv-az787-589:65520] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0e450288ff]
[fv-az787-589:65520] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0e454a5ff5]
[fv-az787-589:65520] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0e454bb0da]
[fv-az787-589:65520] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0e454a5a55]
[fv-az787-589:65520] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0e454a5a6f]
[fv-az787-589:65520] [ 8] plumed(+0x146dd)[0x55b94a4f96dd]
[fv-az787-589:65520] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0e4502a1ca]
[fv-az787-589:65520] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0e4502a28b]
[fv-az787-589:65520] [11] plumed(+0x15365)[0x55b94a4fa365]
[fv-az787-589:65520] *** End of error message ***
</pre>
{% endraw %}
