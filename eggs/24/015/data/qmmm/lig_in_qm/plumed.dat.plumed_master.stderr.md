**Project ID:** [plumID:24.015]({{ '/' | absolute_url }}eggs/24/015/)  
Stderr for source:  qmmm/lig_in_qm/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PATHCV" is not known.
[fv-az1937-158:60832] *** Process received signal ***
[fv-az1937-158:60832] Signal: Aborted (6)
[fv-az1937-158:60832] Signal code:  (-6)
[fv-az1937-158:60832] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1847445330]
[fv-az1937-158:60832] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f184749eb2c]
[fv-az1937-158:60832] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f184744527e]
[fv-az1937-158:60832] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f18474288ff]
[fv-az1937-158:60832] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f18478a5ff5]
[fv-az1937-158:60832] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f18478bb0da]
[fv-az1937-158:60832] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f18478a5a55]
[fv-az1937-158:60832] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f18478a5a6f]
[fv-az1937-158:60832] [ 8] plumed_master(+0x146dd)[0x5645020d96dd]
[fv-az1937-158:60832] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f184742a1ca]
[fv-az1937-158:60832] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f184742a28b]
[fv-az1937-158:60832] [11] plumed_master(+0x15365)[0x5645020da365]
[fv-az1937-158:60832] *** End of error message ***
</pre>
{% endraw %}
