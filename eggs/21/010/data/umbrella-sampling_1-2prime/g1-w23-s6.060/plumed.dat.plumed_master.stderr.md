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
[fv-az802-475:11429] *** Process received signal ***
[fv-az802-475:11429] Signal: Aborted (6)
[fv-az802-475:11429] Signal code:  (-6)
[fv-az802-475:11429] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f20e0845330]
[fv-az802-475:11429] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f20e089eb2c]
[fv-az802-475:11429] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f20e084527e]
[fv-az802-475:11429] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f20e08288ff]
[fv-az802-475:11429] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f20e0ca5ff5]
[fv-az802-475:11429] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f20e0cbb0da]
[fv-az802-475:11429] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f20e0ca5a55]
[fv-az802-475:11429] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f20e0ca5a6f]
[fv-az802-475:11429] [ 8] plumed_master(+0x146dd)[0x561fd1f5c6dd]
[fv-az802-475:11429] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f20e082a1ca]
[fv-az802-475:11429] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f20e082a28b]
[fv-az802-475:11429] [11] plumed_master(+0x15365)[0x561fd1f5d365]
[fv-az802-475:11429] *** End of error message ***
</pre>
{% endraw %}
