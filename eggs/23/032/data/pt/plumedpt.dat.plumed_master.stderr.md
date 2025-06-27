**Project ID:** [plumID:23.032]({{ '/' | absolute_url }}eggs/23/032/)  
Stderr for source:  pt/plumedpt.dat   
Download: [zipped raw stdout](plumedpt.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumedpt.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTORCH_MODEL_CV" is not known.
[pkrvmbietmlfzoi:63819] *** Process received signal ***
[pkrvmbietmlfzoi:63819] Signal: Aborted (6)
[pkrvmbietmlfzoi:63819] Signal code:  (-6)
[pkrvmbietmlfzoi:63819] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6c91245330]
[pkrvmbietmlfzoi:63819] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6c9129eb2c]
[pkrvmbietmlfzoi:63819] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6c9124527e]
[pkrvmbietmlfzoi:63819] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6c912288ff]
[pkrvmbietmlfzoi:63819] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6c916a5ff5]
[pkrvmbietmlfzoi:63819] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6c916bb0da]
[pkrvmbietmlfzoi:63819] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6c916a5a55]
[pkrvmbietmlfzoi:63819] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6c916a5a6f]
[pkrvmbietmlfzoi:63819] [ 8] plumed_master(+0x146dd)[0x55c6a0a986dd]
[pkrvmbietmlfzoi:63819] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6c9122a1ca]
[pkrvmbietmlfzoi:63819] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6c9122a28b]
[pkrvmbietmlfzoi:63819] [11] plumed_master(+0x15365)[0x55c6a0a99365]
[pkrvmbietmlfzoi:63819] *** End of error message ***
</pre>
{% endraw %}
