**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w25-s6.492/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmkj6or:08666] *** Process received signal ***
[runnervmkj6or:08666] Signal: Aborted (6)
[runnervmkj6or:08666] Signal code:  (-6)
[runnervmkj6or:08666] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0a4ee45330]
[runnervmkj6or:08666] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0a4ee9eb2c]
[runnervmkj6or:08666] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0a4ee4527e]
[runnervmkj6or:08666] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0a4ee288ff]
[runnervmkj6or:08666] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0a4f2a5ff5]
[runnervmkj6or:08666] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0a4f2bb0da]
[runnervmkj6or:08666] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0a4f2a5a55]
[runnervmkj6or:08666] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0a4f2a5a6f]
[runnervmkj6or:08666] [ 8] plumed_master(+0x146dd)[0x562862bfd6dd]
[runnervmkj6or:08666] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0a4ee2a1ca]
[runnervmkj6or:08666] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0a4ee2a28b]
[runnervmkj6or:08666] [11] plumed_master(+0x15365)[0x562862bfe365]
[runnervmkj6or:08666] *** End of error message ***
</pre>
{% endraw %}
