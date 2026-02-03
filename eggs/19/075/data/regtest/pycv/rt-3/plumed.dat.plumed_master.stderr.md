**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-3/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[runnervmkj6or:11328] *** Process received signal ***
[runnervmkj6or:11328] Signal: Aborted (6)
[runnervmkj6or:11328] Signal code:  (-6)
[runnervmkj6or:11328] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f126bc45330]
[runnervmkj6or:11328] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f126bc9eb2c]
[runnervmkj6or:11328] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f126bc4527e]
[runnervmkj6or:11328] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f126bc288ff]
[runnervmkj6or:11328] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f126c0a5ff5]
[runnervmkj6or:11328] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f126c0bb0da]
[runnervmkj6or:11328] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f126c0a5a55]
[runnervmkj6or:11328] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f126c0a5a6f]
[runnervmkj6or:11328] [ 8] plumed_master(+0x146dd)[0x55ae748b06dd]
[runnervmkj6or:11328] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f126bc2a1ca]
[runnervmkj6or:11328] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f126bc2a28b]
[runnervmkj6or:11328] [11] plumed_master(+0x15365)[0x55ae748b1365]
[runnervmkj6or:11328] *** End of error message ***
</pre>
{% endraw %}
