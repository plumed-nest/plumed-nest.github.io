**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-jax1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[fv-az1719-82:69408] *** Process received signal ***
[fv-az1719-82:69408] Signal: Aborted (6)
[fv-az1719-82:69408] Signal code:  (-6)
[fv-az1719-82:69408] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f746a045330]
[fv-az1719-82:69408] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f746a09eb2c]
[fv-az1719-82:69408] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f746a04527e]
[fv-az1719-82:69408] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f746a0288ff]
[fv-az1719-82:69408] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f746a4a5ff5]
[fv-az1719-82:69408] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f746a4bb0da]
[fv-az1719-82:69408] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f746a4a5a55]
[fv-az1719-82:69408] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f746a4a5a6f]
[fv-az1719-82:69408] [ 8] plumed_master(+0x146dd)[0x55931f3606dd]
[fv-az1719-82:69408] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f746a02a1ca]
[fv-az1719-82:69408] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f746a02a28b]
[fv-az1719-82:69408] [11] plumed_master(+0x15365)[0x55931f361365]
[fv-az1719-82:69408] *** End of error message ***
</pre>
{% endraw %}
