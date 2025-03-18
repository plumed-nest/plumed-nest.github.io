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
[fv-az790-36:66926] *** Process received signal ***
[fv-az790-36:66926] Signal: Aborted (6)
[fv-az790-36:66926] Signal code:  (-6)
[fv-az790-36:66926] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0800245330]
[fv-az790-36:66926] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f080029eb2c]
[fv-az790-36:66926] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f080024527e]
[fv-az790-36:66926] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f08002288ff]
[fv-az790-36:66926] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f08006a5ff5]
[fv-az790-36:66926] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f08006bb0da]
[fv-az790-36:66926] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f08006a5a55]
[fv-az790-36:66926] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f08006a5a6f]
[fv-az790-36:66926] [ 8] plumed_master(+0x146dd)[0x557021e646dd]
[fv-az790-36:66926] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f080022a1ca]
[fv-az790-36:66926] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f080022a28b]
[fv-az790-36:66926] [11] plumed_master(+0x15365)[0x557021e65365]
[fv-az790-36:66926] *** End of error message ***
</pre>
{% endraw %}
