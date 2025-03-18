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
[fv-az1983-395:61503] *** Process received signal ***
[fv-az1983-395:61503] Signal: Aborted (6)
[fv-az1983-395:61503] Signal code:  (-6)
[fv-az1983-395:61503] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff0af245330]
[fv-az1983-395:61503] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff0af29eb2c]
[fv-az1983-395:61503] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff0af24527e]
[fv-az1983-395:61503] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff0af2288ff]
[fv-az1983-395:61503] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff0af6a5ff5]
[fv-az1983-395:61503] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff0af6bb0da]
[fv-az1983-395:61503] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff0af6a5a55]
[fv-az1983-395:61503] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff0af6a5a6f]
[fv-az1983-395:61503] [ 8] plumed_master(+0x146dd)[0x55c97c50f6dd]
[fv-az1983-395:61503] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff0af22a1ca]
[fv-az1983-395:61503] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff0af22a28b]
[fv-az1983-395:61503] [11] plumed_master(+0x15365)[0x55c97c510365]
[fv-az1983-395:61503] *** End of error message ***
</pre>
{% endraw %}
