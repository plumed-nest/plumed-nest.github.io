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
[fv-az1719-82:69562] *** Process received signal ***
[fv-az1719-82:69562] Signal: Aborted (6)
[fv-az1719-82:69562] Signal code:  (-6)
[fv-az1719-82:69562] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7728a45330]
[fv-az1719-82:69562] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7728a9eb2c]
[fv-az1719-82:69562] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7728a4527e]
[fv-az1719-82:69562] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7728a288ff]
[fv-az1719-82:69562] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7728ea5ff5]
[fv-az1719-82:69562] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7728ebb0da]
[fv-az1719-82:69562] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7728ea5a55]
[fv-az1719-82:69562] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7728ea5a6f]
[fv-az1719-82:69562] [ 8] plumed_master(+0x146dd)[0x56500bf9b6dd]
[fv-az1719-82:69562] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7728a2a1ca]
[fv-az1719-82:69562] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7728a2a28b]
[fv-az1719-82:69562] [11] plumed_master(+0x15365)[0x56500bf9c365]
[fv-az1719-82:69562] *** End of error message ***
</pre>
{% endraw %}
