**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w23-s6.060/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az790-36:66910] *** Process received signal ***
[fv-az790-36:66910] Signal: Aborted (6)
[fv-az790-36:66910] Signal code:  (-6)
[fv-az790-36:66910] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f34a8445330]
[fv-az790-36:66910] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f34a849eb2c]
[fv-az790-36:66910] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f34a844527e]
[fv-az790-36:66910] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f34a84288ff]
[fv-az790-36:66910] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f34a88a5ff5]
[fv-az790-36:66910] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f34a88bb0da]
[fv-az790-36:66910] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f34a88a5a55]
[fv-az790-36:66910] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f34a88a5a6f]
[fv-az790-36:66910] [ 8] plumed(+0x146dd)[0x55b1a056c6dd]
[fv-az790-36:66910] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f34a842a1ca]
[fv-az790-36:66910] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f34a842a28b]
[fv-az790-36:66910] [11] plumed(+0x15365)[0x55b1a056d365]
[fv-az790-36:66910] *** End of error message ***
</pre>
{% endraw %}
