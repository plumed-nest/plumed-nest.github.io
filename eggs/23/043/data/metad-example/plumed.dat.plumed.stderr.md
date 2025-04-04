**Project ID:** [plumID:23.043]({{ '/' | absolute_url }}eggs/23/043/)  
Stderr for source:  metad-example/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "SPHERICAL_EXPANSION" is not known.
[fv-az1624-565:05671] *** Process received signal ***
[fv-az1624-565:05671] Signal: Aborted (6)
[fv-az1624-565:05671] Signal code:  (-6)
[fv-az1624-565:05671] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9e05045330]
[fv-az1624-565:05671] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9e0509eb2c]
[fv-az1624-565:05671] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9e0504527e]
[fv-az1624-565:05671] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9e050288ff]
[fv-az1624-565:05671] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9e054a5ff5]
[fv-az1624-565:05671] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9e054bb0da]
[fv-az1624-565:05671] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9e054a5a55]
[fv-az1624-565:05671] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9e054a5a6f]
[fv-az1624-565:05671] [ 8] plumed(+0x146dd)[0x5597e16c96dd]
[fv-az1624-565:05671] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9e0502a1ca]
[fv-az1624-565:05671] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9e0502a28b]
[fv-az1624-565:05671] [11] plumed(+0x15365)[0x5597e16ca365]
[fv-az1624-565:05671] *** End of error message ***
</pre>
{% endraw %}
