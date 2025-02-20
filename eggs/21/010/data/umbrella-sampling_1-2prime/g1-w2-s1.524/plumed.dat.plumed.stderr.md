**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w2-s1.524/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az802-475:11204] *** Process received signal ***
[fv-az802-475:11204] Signal: Aborted (6)
[fv-az802-475:11204] Signal code:  (-6)
[fv-az802-475:11204] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa26c045330]
[fv-az802-475:11204] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa26c09eb2c]
[fv-az802-475:11204] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa26c04527e]
[fv-az802-475:11204] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa26c0288ff]
[fv-az802-475:11204] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa26c4a5ff5]
[fv-az802-475:11204] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa26c4bb0da]
[fv-az802-475:11204] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa26c4a5a55]
[fv-az802-475:11204] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa26c4a5a6f]
[fv-az802-475:11204] [ 8] plumed(+0x146dd)[0x55a3047fe6dd]
[fv-az802-475:11204] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa26c02a1ca]
[fv-az802-475:11204] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa26c02a28b]
[fv-az802-475:11204] [11] plumed(+0x15365)[0x55a3047ff365]
[fv-az802-475:11204] *** End of error message ***
</pre>
{% endraw %}
