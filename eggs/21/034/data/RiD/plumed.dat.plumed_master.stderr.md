**Project ID:** [plumID:21.034]({{ '/' | absolute_url }}eggs/21/034/)  
Stderr for source:  RiD/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "DEEPFE" is not known.
[fv-az1680-626:10627] *** Process received signal ***
[fv-az1680-626:10627] Signal: Aborted (6)
[fv-az1680-626:10627] Signal code:  (-6)
[fv-az1680-626:10627] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4dd7445330]
[fv-az1680-626:10627] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4dd749eb2c]
[fv-az1680-626:10627] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4dd744527e]
[fv-az1680-626:10627] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4dd74288ff]
[fv-az1680-626:10627] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4dd78a5ff5]
[fv-az1680-626:10627] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4dd78bb0da]
[fv-az1680-626:10627] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4dd78a5a55]
[fv-az1680-626:10627] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4dd78a5a6f]
[fv-az1680-626:10627] [ 8] plumed_master(+0x146dd)[0x55ab62f466dd]
[fv-az1680-626:10627] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4dd742a1ca]
[fv-az1680-626:10627] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4dd742a28b]
[fv-az1680-626:10627] [11] plumed_master(+0x15365)[0x55ab62f47365]
[fv-az1680-626:10627] *** End of error message ***
</pre>
{% endraw %}
