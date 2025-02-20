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
[fv-az802-475:11361] *** Process received signal ***
[fv-az802-475:11361] Signal: Aborted (6)
[fv-az802-475:11361] Signal code:  (-6)
[fv-az802-475:11361] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbdcc845330]
[fv-az802-475:11361] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbdcc89eb2c]
[fv-az802-475:11361] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbdcc84527e]
[fv-az802-475:11361] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbdcc8288ff]
[fv-az802-475:11361] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbdccca5ff5]
[fv-az802-475:11361] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbdcccbb0da]
[fv-az802-475:11361] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbdccca5a55]
[fv-az802-475:11361] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbdccca5a6f]
[fv-az802-475:11361] [ 8] plumed(+0x146dd)[0x56255f5196dd]
[fv-az802-475:11361] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbdcc82a1ca]
[fv-az802-475:11361] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbdcc82a28b]
[fv-az802-475:11361] [11] plumed(+0x15365)[0x56255f51a365]
[fv-az802-475:11361] *** End of error message ***
</pre>
{% endraw %}
