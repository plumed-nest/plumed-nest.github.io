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
[pkrvmbietmlfzoi:07655] *** Process received signal ***
[pkrvmbietmlfzoi:07655] Signal: Aborted (6)
[pkrvmbietmlfzoi:07655] Signal code:  (-6)
[pkrvmbietmlfzoi:07655] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5298245330]
[pkrvmbietmlfzoi:07655] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f529829eb2c]
[pkrvmbietmlfzoi:07655] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f529824527e]
[pkrvmbietmlfzoi:07655] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f52982288ff]
[pkrvmbietmlfzoi:07655] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f52986a5ff5]
[pkrvmbietmlfzoi:07655] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f52986bb0da]
[pkrvmbietmlfzoi:07655] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f52986a5a55]
[pkrvmbietmlfzoi:07655] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f52986a5a6f]
[pkrvmbietmlfzoi:07655] [ 8] plumed_master(+0x146dd)[0x55d9976a56dd]
[pkrvmbietmlfzoi:07655] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f529822a1ca]
[pkrvmbietmlfzoi:07655] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f529822a28b]
[pkrvmbietmlfzoi:07655] [11] plumed_master(+0x15365)[0x55d9976a6365]
[pkrvmbietmlfzoi:07655] *** End of error message ***
</pre>
{% endraw %}
