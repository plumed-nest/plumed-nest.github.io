**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-f2/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONFUNCTION" is not known.
[fv-az1719-82:69357] *** Process received signal ***
[fv-az1719-82:69357] Signal: Aborted (6)
[fv-az1719-82:69357] Signal code:  (-6)
[fv-az1719-82:69357] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7efc22045330]
[fv-az1719-82:69357] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7efc2209eb2c]
[fv-az1719-82:69357] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7efc2204527e]
[fv-az1719-82:69357] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7efc220288ff]
[fv-az1719-82:69357] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7efc224a5ff5]
[fv-az1719-82:69357] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7efc224bb0da]
[fv-az1719-82:69357] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7efc224a5a55]
[fv-az1719-82:69357] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7efc224a5a6f]
[fv-az1719-82:69357] [ 8] plumed_master(+0x146dd)[0x557024b666dd]
[fv-az1719-82:69357] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7efc2202a1ca]
[fv-az1719-82:69357] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7efc2202a28b]
[fv-az1719-82:69357] [11] plumed_master(+0x15365)[0x557024b67365]
[fv-az1719-82:69357] *** End of error message ***
</pre>
{% endraw %}
