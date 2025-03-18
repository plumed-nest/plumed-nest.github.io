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
[fv-az1377-740:60887] *** Process received signal ***
[fv-az1377-740:60887] Signal: Aborted (6)
[fv-az1377-740:60887] Signal code:  (-6)
[fv-az1377-740:60887] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f63d5845330]
[fv-az1377-740:60887] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f63d589eb2c]
[fv-az1377-740:60887] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f63d584527e]
[fv-az1377-740:60887] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f63d58288ff]
[fv-az1377-740:60887] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f63d5ca5ff5]
[fv-az1377-740:60887] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f63d5cbb0da]
[fv-az1377-740:60887] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f63d5ca5a55]
[fv-az1377-740:60887] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f63d5ca5a6f]
[fv-az1377-740:60887] [ 8] plumed_master(+0x146dd)[0x56179d51f6dd]
[fv-az1377-740:60887] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f63d582a1ca]
[fv-az1377-740:60887] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f63d582a28b]
[fv-az1377-740:60887] [11] plumed_master(+0x15365)[0x56179d520365]
[fv-az1377-740:60887] *** End of error message ***
</pre>
{% endraw %}
