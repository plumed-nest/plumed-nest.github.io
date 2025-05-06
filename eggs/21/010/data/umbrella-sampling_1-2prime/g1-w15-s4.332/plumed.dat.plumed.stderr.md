**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w15-s4.332/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az2209-645:65417] *** Process received signal ***
[fv-az2209-645:65417] Signal: Aborted (6)
[fv-az2209-645:65417] Signal code:  (-6)
[fv-az2209-645:65417] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f430e045330]
[fv-az2209-645:65417] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f430e09eb2c]
[fv-az2209-645:65417] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f430e04527e]
[fv-az2209-645:65417] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f430e0288ff]
[fv-az2209-645:65417] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f430e4a5ff5]
[fv-az2209-645:65417] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f430e4bb0da]
[fv-az2209-645:65417] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f430e4a5a55]
[fv-az2209-645:65417] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f430e4a5a6f]
[fv-az2209-645:65417] [ 8] plumed(+0x146dd)[0x55e208b416dd]
[fv-az2209-645:65417] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f430e02a1ca]
[fv-az2209-645:65417] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f430e02a28b]
[fv-az2209-645:65417] [11] plumed(+0x15365)[0x55e208b42365]
[fv-az2209-645:65417] *** End of error message ***
</pre>
{% endraw %}
