**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-multi-1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[pkrvmf6wy0o8zjz:69331] *** Process received signal ***
[pkrvmf6wy0o8zjz:69331] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:69331] Signal code:  (-6)
[pkrvmf6wy0o8zjz:69331] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f62aaa45330]
[pkrvmf6wy0o8zjz:69331] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f62aaa9eb2c]
[pkrvmf6wy0o8zjz:69331] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f62aaa4527e]
[pkrvmf6wy0o8zjz:69331] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f62aaa288ff]
[pkrvmf6wy0o8zjz:69331] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f62aaea5ff5]
[pkrvmf6wy0o8zjz:69331] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f62aaebb0da]
[pkrvmf6wy0o8zjz:69331] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f62aaea5a55]
[pkrvmf6wy0o8zjz:69331] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f62aaea5a6f]
[pkrvmf6wy0o8zjz:69331] [ 8] plumed_master(+0x146dd)[0x564d0897f6dd]
[pkrvmf6wy0o8zjz:69331] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f62aaa2a1ca]
[pkrvmf6wy0o8zjz:69331] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f62aaa2a28b]
[pkrvmf6wy0o8zjz:69331] [11] plumed_master(+0x15365)[0x564d08980365]
[pkrvmf6wy0o8zjz:69331] *** End of error message ***
</pre>
{% endraw %}
