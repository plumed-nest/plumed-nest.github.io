**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/atlas_3d/res/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATLAS" is not known.
[fv-az787-589:64076] *** Process received signal ***
[fv-az787-589:64076] Signal: Aborted (6)
[fv-az787-589:64076] Signal code:  (-6)
[fv-az787-589:64076] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fab7c245330]
[fv-az787-589:64076] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fab7c29eb2c]
[fv-az787-589:64076] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fab7c24527e]
[fv-az787-589:64076] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fab7c2288ff]
[fv-az787-589:64076] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fab7c6a5ff5]
[fv-az787-589:64076] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fab7c6bb0da]
[fv-az787-589:64076] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fab7c6a5a55]
[fv-az787-589:64076] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fab7c6a5a6f]
[fv-az787-589:64076] [ 8] plumed(+0x146dd)[0x55c3778926dd]
[fv-az787-589:64076] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fab7c22a1ca]
[fv-az787-589:64076] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fab7c22a28b]
[fv-az787-589:64076] [11] plumed(+0x15365)[0x55c377893365]
[fv-az787-589:64076] *** End of error message ***
</pre>
{% endraw %}
