**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w27-s6.924/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az2209-645:66105] *** Process received signal ***
[fv-az2209-645:66105] Signal: Aborted (6)
[fv-az2209-645:66105] Signal code:  (-6)
[fv-az2209-645:66105] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f151ee45330]
[fv-az2209-645:66105] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f151ee9eb2c]
[fv-az2209-645:66105] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f151ee4527e]
[fv-az2209-645:66105] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f151ee288ff]
[fv-az2209-645:66105] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f151f2a5ff5]
[fv-az2209-645:66105] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f151f2bb0da]
[fv-az2209-645:66105] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f151f2a5a55]
[fv-az2209-645:66105] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f151f2a5a6f]
[fv-az2209-645:66105] [ 8] plumed_master(+0x146dd)[0x55b62d8d36dd]
[fv-az2209-645:66105] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f151ee2a1ca]
[fv-az2209-645:66105] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f151ee2a28b]
[fv-az2209-645:66105] [11] plumed_master(+0x15365)[0x55b62d8d4365]
[fv-az2209-645:66105] *** End of error message ***
</pre>
{% endraw %}
