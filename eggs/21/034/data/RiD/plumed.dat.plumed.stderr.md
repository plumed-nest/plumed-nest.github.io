**Project ID:** [plumID:21.034]({{ '/' | absolute_url }}eggs/21/034/)  
Stderr for source:  RiD/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "DEEPFE" is not known.
[fv-az1680-626:10611] *** Process received signal ***
[fv-az1680-626:10611] Signal: Aborted (6)
[fv-az1680-626:10611] Signal code:  (-6)
[fv-az1680-626:10611] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc5cee45330]
[fv-az1680-626:10611] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc5cee9eb2c]
[fv-az1680-626:10611] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc5cee4527e]
[fv-az1680-626:10611] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc5cee288ff]
[fv-az1680-626:10611] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc5cf2a5ff5]
[fv-az1680-626:10611] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc5cf2bb0da]
[fv-az1680-626:10611] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc5cf2a5a55]
[fv-az1680-626:10611] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc5cf2a5a6f]
[fv-az1680-626:10611] [ 8] plumed(+0x146dd)[0x56392cff16dd]
[fv-az1680-626:10611] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc5cee2a1ca]
[fv-az1680-626:10611] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc5cee2a28b]
[fv-az1680-626:10611] [11] plumed(+0x15365)[0x56392cff2365]
[fv-az1680-626:10611] *** End of error message ***
</pre>
{% endraw %}
