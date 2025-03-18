**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/tetra_pept/plumed_biased.dat   
Download: [zipped raw stdout](plumed_biased.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_biased.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATLAS" is not known.
[fv-az1377-740:64449] *** Process received signal ***
[fv-az1377-740:64449] Signal: Aborted (6)
[fv-az1377-740:64449] Signal code:  (-6)
[fv-az1377-740:64449] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb16fc45330]
[fv-az1377-740:64449] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb16fc9eb2c]
[fv-az1377-740:64449] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb16fc4527e]
[fv-az1377-740:64449] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb16fc288ff]
[fv-az1377-740:64449] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb1700a5ff5]
[fv-az1377-740:64449] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb1700bb0da]
[fv-az1377-740:64449] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb1700a5a55]
[fv-az1377-740:64449] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb1700a5a6f]
[fv-az1377-740:64449] [ 8] plumed_master(+0x146dd)[0x5636f135d6dd]
[fv-az1377-740:64449] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb16fc2a1ca]
[fv-az1377-740:64449] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb16fc2a28b]
[fv-az1377-740:64449] [11] plumed_master(+0x15365)[0x5636f135e365]
[fv-az1377-740:64449] *** End of error message ***
</pre>
{% endraw %}
