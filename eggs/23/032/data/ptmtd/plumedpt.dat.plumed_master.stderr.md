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
[fv-az1370-99:61473] *** Process received signal ***
[fv-az1370-99:61473] Signal: Aborted (6)
[fv-az1370-99:61473] Signal code:  (-6)
[fv-az1370-99:61473] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb5d6645330]
[fv-az1370-99:61473] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb5d669eb2c]
[fv-az1370-99:61473] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb5d664527e]
[fv-az1370-99:61473] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb5d66288ff]
[fv-az1370-99:61473] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb5d6aa5ff5]
[fv-az1370-99:61473] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb5d6abb0da]
[fv-az1370-99:61473] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb5d6aa5a55]
[fv-az1370-99:61473] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb5d6aa5a6f]
[fv-az1370-99:61473] [ 8] plumed_master(+0x146dd)[0x55f204ec36dd]
[fv-az1370-99:61473] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb5d662a1ca]
[fv-az1370-99:61473] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb5d662a28b]
[fv-az1370-99:61473] [11] plumed_master(+0x15365)[0x55f204ec4365]
[fv-az1370-99:61473] *** End of error message ***
</pre>
{% endraw %}
