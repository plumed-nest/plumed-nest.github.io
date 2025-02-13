**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w22-s5.844/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az1390-170:10923] *** Process received signal ***
[fv-az1390-170:10923] Signal: Aborted (6)
[fv-az1390-170:10923] Signal code:  (-6)
[fv-az1390-170:10923] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7829a45330]
[fv-az1390-170:10923] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7829a9eb2c]
[fv-az1390-170:10923] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7829a4527e]
[fv-az1390-170:10923] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7829a288ff]
[fv-az1390-170:10923] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7829ea5ff5]
[fv-az1390-170:10923] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7829ebb0da]
[fv-az1390-170:10923] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7829ea5a55]
[fv-az1390-170:10923] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7829ea5a6f]
[fv-az1390-170:10923] [ 8] plumed(+0x146dd)[0x55672c1e66dd]
[fv-az1390-170:10923] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7829a2a1ca]
[fv-az1390-170:10923] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7829a2a28b]
[fv-az1390-170:10923] [11] plumed(+0x15365)[0x55672c1e7365]
[fv-az1390-170:10923] *** End of error message ***
</pre>
{% endraw %}
