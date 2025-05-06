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
[fv-az1696-883:67611] *** Process received signal ***
[fv-az1696-883:67611] Signal: Aborted (6)
[fv-az1696-883:67611] Signal code:  (-6)
[fv-az1696-883:67611] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fce8c445330]
[fv-az1696-883:67611] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fce8c49eb2c]
[fv-az1696-883:67611] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fce8c44527e]
[fv-az1696-883:67611] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fce8c4288ff]
[fv-az1696-883:67611] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fce8c8a5ff5]
[fv-az1696-883:67611] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fce8c8bb0da]
[fv-az1696-883:67611] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fce8c8a5a55]
[fv-az1696-883:67611] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fce8c8a5a6f]
[fv-az1696-883:67611] [ 8] plumed_master(+0x146dd)[0x555ca8d1f6dd]
[fv-az1696-883:67611] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fce8c42a1ca]
[fv-az1696-883:67611] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fce8c42a28b]
[fv-az1696-883:67611] [11] plumed_master(+0x15365)[0x555ca8d20365]
[fv-az1696-883:67611] *** End of error message ***
</pre>
{% endraw %}
