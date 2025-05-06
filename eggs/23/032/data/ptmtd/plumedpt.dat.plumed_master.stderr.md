**Project ID:** [plumID:23.032]({{ '/' | absolute_url }}eggs/23/032/)  
Stderr for source:  ptmtd/plumedpt.dat   
Download: [zipped raw stdout](plumedpt.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumedpt.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTORCH_MODEL_CV" is not known.
[fv-az1110-827:61138] *** Process received signal ***
[fv-az1110-827:61138] Signal: Aborted (6)
[fv-az1110-827:61138] Signal code:  (-6)
[fv-az1110-827:61138] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7faa44445330]
[fv-az1110-827:61138] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7faa4449eb2c]
[fv-az1110-827:61138] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7faa4444527e]
[fv-az1110-827:61138] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7faa444288ff]
[fv-az1110-827:61138] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7faa448a5ff5]
[fv-az1110-827:61138] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7faa448bb0da]
[fv-az1110-827:61138] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7faa448a5a55]
[fv-az1110-827:61138] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7faa448a5a6f]
[fv-az1110-827:61138] [ 8] plumed_master(+0x146dd)[0x5641329fb6dd]
[fv-az1110-827:61138] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7faa4442a1ca]
[fv-az1110-827:61138] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7faa4442a28b]
[fv-az1110-827:61138] [11] plumed_master(+0x15365)[0x5641329fc365]
[fv-az1110-827:61138] *** End of error message ***
</pre>
{% endraw %}
