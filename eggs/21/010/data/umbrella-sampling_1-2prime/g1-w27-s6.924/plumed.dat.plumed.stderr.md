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
[fv-az802-475:11679] *** Process received signal ***
[fv-az802-475:11679] Signal: Aborted (6)
[fv-az802-475:11679] Signal code:  (-6)
[fv-az802-475:11679] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc87c845330]
[fv-az802-475:11679] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc87c89eb2c]
[fv-az802-475:11679] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc87c84527e]
[fv-az802-475:11679] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc87c8288ff]
[fv-az802-475:11679] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc87cca5ff5]
[fv-az802-475:11679] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc87ccbb0da]
[fv-az802-475:11679] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc87cca5a55]
[fv-az802-475:11679] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc87cca5a6f]
[fv-az802-475:11679] [ 8] plumed(+0x146dd)[0x5568662b76dd]
[fv-az802-475:11679] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc87c82a1ca]
[fv-az802-475:11679] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc87c82a28b]
[fv-az802-475:11679] [11] plumed(+0x15365)[0x5568662b8365]
[fv-az802-475:11679] *** End of error message ***
</pre>
{% endraw %}
