**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  FFH_scripts/plumed_FFH.dat   
Download: [zipped raw stdout](plumed_FFH.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_FFH.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATLAS" is not known.
[fv-az1280-696:09514] *** Process received signal ***
[fv-az1280-696:09514] Signal: Aborted (6)
[fv-az1280-696:09514] Signal code:  (-6)
[fv-az1280-696:09514] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbfa8445330]
[fv-az1280-696:09514] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbfa849eb2c]
[fv-az1280-696:09514] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbfa844527e]
[fv-az1280-696:09514] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbfa84288ff]
[fv-az1280-696:09514] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbfa88a5ff5]
[fv-az1280-696:09514] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbfa88bb0da]
[fv-az1280-696:09514] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbfa88a5a55]
[fv-az1280-696:09514] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbfa88a5a6f]
[fv-az1280-696:09514] [ 8] plumed(+0x146dd)[0x555cb67b66dd]
[fv-az1280-696:09514] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbfa842a1ca]
[fv-az1280-696:09514] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbfa842a28b]
[fv-az1280-696:09514] [11] plumed(+0x15365)[0x555cb67b7365]
[fv-az1280-696:09514] *** End of error message ***
</pre>
{% endraw %}
