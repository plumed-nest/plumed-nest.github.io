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
[fv-az1691-811:06918] *** Process received signal ***
[fv-az1691-811:06918] Signal: Aborted (6)
[fv-az1691-811:06918] Signal code:  (-6)
[fv-az1691-811:06918] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fdb52045330]
[fv-az1691-811:06918] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fdb5209eb2c]
[fv-az1691-811:06918] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fdb5204527e]
[fv-az1691-811:06918] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fdb520288ff]
[fv-az1691-811:06918] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fdb524a5ff5]
[fv-az1691-811:06918] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fdb524bb0da]
[fv-az1691-811:06918] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fdb524a5a55]
[fv-az1691-811:06918] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fdb524a5a6f]
[fv-az1691-811:06918] [ 8] plumed(+0x146dd)[0x55609ed046dd]
[fv-az1691-811:06918] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fdb5202a1ca]
[fv-az1691-811:06918] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fdb5202a28b]
[fv-az1691-811:06918] [11] plumed(+0x15365)[0x55609ed05365]
[fv-az1691-811:06918] *** End of error message ***
</pre>
{% endraw %}
