**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w23-s6.060/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az2209-645:65900] *** Process received signal ***
[fv-az2209-645:65900] Signal: Aborted (6)
[fv-az2209-645:65900] Signal code:  (-6)
[fv-az2209-645:65900] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5c5ea45330]
[fv-az2209-645:65900] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5c5ea9eb2c]
[fv-az2209-645:65900] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5c5ea4527e]
[fv-az2209-645:65900] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5c5ea288ff]
[fv-az2209-645:65900] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5c5eea5ff5]
[fv-az2209-645:65900] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5c5eebb0da]
[fv-az2209-645:65900] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5c5eea5a55]
[fv-az2209-645:65900] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5c5eea5a6f]
[fv-az2209-645:65900] [ 8] plumed_master(+0x146dd)[0x56342e9a36dd]
[fv-az2209-645:65900] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5c5ea2a1ca]
[fv-az2209-645:65900] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5c5ea2a28b]
[fv-az2209-645:65900] [11] plumed_master(+0x15365)[0x56342e9a4365]
[fv-az2209-645:65900] *** End of error message ***
</pre>
{% endraw %}
