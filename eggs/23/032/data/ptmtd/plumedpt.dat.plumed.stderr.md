**Project ID:** [plumID:23.032]({{ '/' | absolute_url }}eggs/23/032/)  
Stderr for source:  ptmtd/plumedpt.dat   
Download: [zipped raw stdout](plumedpt.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumedpt.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTORCH_MODEL_CV" is not known.
[fv-az1360-658:08152] *** Process received signal ***
[fv-az1360-658:08152] Signal: Aborted (6)
[fv-az1360-658:08152] Signal code:  (-6)
[fv-az1360-658:08152] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7c87645330]
[fv-az1360-658:08152] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7c8769eb2c]
[fv-az1360-658:08152] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7c8764527e]
[fv-az1360-658:08152] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7c876288ff]
[fv-az1360-658:08152] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7c87aa5ff5]
[fv-az1360-658:08152] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7c87abb0da]
[fv-az1360-658:08152] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7c87aa5a55]
[fv-az1360-658:08152] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7c87aa5a6f]
[fv-az1360-658:08152] [ 8] plumed(+0x146dd)[0x55c4a9c736dd]
[fv-az1360-658:08152] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7c8762a1ca]
[fv-az1360-658:08152] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7c8762a28b]
[fv-az1360-658:08152] [11] plumed(+0x15365)[0x55c4a9c74365]
[fv-az1360-658:08152] *** End of error message ***
</pre>
{% endraw %}
