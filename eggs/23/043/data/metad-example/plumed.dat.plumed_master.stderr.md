**Project ID:** [plumID:23.043]({{ '/' | absolute_url }}eggs/23/043/)  
Stderr for source:  metad-example/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "SPHERICAL_EXPANSION" is not known.
[fv-az1624-565:05687] *** Process received signal ***
[fv-az1624-565:05687] Signal: Aborted (6)
[fv-az1624-565:05687] Signal code:  (-6)
[fv-az1624-565:05687] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff5c8e45330]
[fv-az1624-565:05687] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff5c8e9eb2c]
[fv-az1624-565:05687] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff5c8e4527e]
[fv-az1624-565:05687] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff5c8e288ff]
[fv-az1624-565:05687] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff5c92a5ff5]
[fv-az1624-565:05687] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff5c92bb0da]
[fv-az1624-565:05687] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff5c92a5a55]
[fv-az1624-565:05687] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff5c92a5a6f]
[fv-az1624-565:05687] [ 8] plumed_master(+0x146dd)[0x55f74dd6e6dd]
[fv-az1624-565:05687] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff5c8e2a1ca]
[fv-az1624-565:05687] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff5c8e2a28b]
[fv-az1624-565:05687] [11] plumed_master(+0x15365)[0x55f74dd6f365]
[fv-az1624-565:05687] *** End of error message ***
</pre>
{% endraw %}
