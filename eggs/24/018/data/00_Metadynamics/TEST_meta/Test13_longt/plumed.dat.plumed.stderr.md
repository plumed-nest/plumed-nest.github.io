**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test13_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmkj6or:07074] *** Process received signal ***
[runnervmkj6or:07074] Signal: Aborted (6)
[runnervmkj6or:07074] Signal code:  (-6)
[runnervmkj6or:07074] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f28f9e45330]
[runnervmkj6or:07074] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f28f9e9eb2c]
[runnervmkj6or:07074] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f28f9e4527e]
[runnervmkj6or:07074] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f28f9e288ff]
[runnervmkj6or:07074] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f28fa2a5ff5]
[runnervmkj6or:07074] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f28fa2bb0da]
[runnervmkj6or:07074] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f28fa2a5a55]
[runnervmkj6or:07074] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f28fa2a5a6f]
[runnervmkj6or:07074] [ 8] plumed(+0x146dd)[0x55722b1326dd]
[runnervmkj6or:07074] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f28f9e2a1ca]
[runnervmkj6or:07074] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f28f9e2a28b]
[runnervmkj6or:07074] [11] plumed(+0x15365)[0x55722b133365]
[runnervmkj6or:07074] *** End of error message ***
</pre>
{% endraw %}
