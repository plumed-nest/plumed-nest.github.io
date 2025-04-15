**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-f1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONFUNCTION" is not known.
[fv-az1719-82:69306] *** Process received signal ***
[fv-az1719-82:69306] Signal: Aborted (6)
[fv-az1719-82:69306] Signal code:  (-6)
[fv-az1719-82:69306] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8591045330]
[fv-az1719-82:69306] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f859109eb2c]
[fv-az1719-82:69306] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f859104527e]
[fv-az1719-82:69306] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f85910288ff]
[fv-az1719-82:69306] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f85914a5ff5]
[fv-az1719-82:69306] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f85914bb0da]
[fv-az1719-82:69306] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f85914a5a55]
[fv-az1719-82:69306] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f85914a5a6f]
[fv-az1719-82:69306] [ 8] plumed_master(+0x146dd)[0x5572d6f436dd]
[fv-az1719-82:69306] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f859102a1ca]
[fv-az1719-82:69306] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f859102a28b]
[fv-az1719-82:69306] [11] plumed_master(+0x15365)[0x5572d6f44365]
[fv-az1719-82:69306] *** End of error message ***
</pre>
{% endraw %}
