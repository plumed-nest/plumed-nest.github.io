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
[fv-az1370-99:61457] *** Process received signal ***
[fv-az1370-99:61457] Signal: Aborted (6)
[fv-az1370-99:61457] Signal code:  (-6)
[fv-az1370-99:61457] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc005c45330]
[fv-az1370-99:61457] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc005c9eb2c]
[fv-az1370-99:61457] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc005c4527e]
[fv-az1370-99:61457] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc005c288ff]
[fv-az1370-99:61457] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc0060a5ff5]
[fv-az1370-99:61457] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc0060bb0da]
[fv-az1370-99:61457] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc0060a5a55]
[fv-az1370-99:61457] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc0060a5a6f]
[fv-az1370-99:61457] [ 8] plumed(+0x146dd)[0x5617c556a6dd]
[fv-az1370-99:61457] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc005c2a1ca]
[fv-az1370-99:61457] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc005c2a28b]
[fv-az1370-99:61457] [11] plumed(+0x15365)[0x5617c556b365]
[fv-az1370-99:61457] *** End of error message ***
</pre>
{% endraw %}
