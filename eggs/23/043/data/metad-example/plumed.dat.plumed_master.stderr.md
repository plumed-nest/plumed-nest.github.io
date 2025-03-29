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
[fv-az1701-508:62304] *** Process received signal ***
[fv-az1701-508:62304] Signal: Aborted (6)
[fv-az1701-508:62304] Signal code:  (-6)
[fv-az1701-508:62304] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbc50445330]
[fv-az1701-508:62304] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbc5049eb2c]
[fv-az1701-508:62304] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbc5044527e]
[fv-az1701-508:62304] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbc504288ff]
[fv-az1701-508:62304] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbc508a5ff5]
[fv-az1701-508:62304] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbc508bb0da]
[fv-az1701-508:62304] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbc508a5a55]
[fv-az1701-508:62304] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbc508a5a6f]
[fv-az1701-508:62304] [ 8] plumed_master(+0x146dd)[0x562391cf76dd]
[fv-az1701-508:62304] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbc5042a1ca]
[fv-az1701-508:62304] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbc5042a28b]
[fv-az1701-508:62304] [11] plumed_master(+0x15365)[0x562391cf8365]
[fv-az1701-508:62304] *** End of error message ***
</pre>
{% endraw %}
