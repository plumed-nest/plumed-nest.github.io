**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/atlas_2d/pca_2/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATLAS" is not known.
[fv-az1377-740:64034] *** Process received signal ***
[fv-az1377-740:64034] Signal: Aborted (6)
[fv-az1377-740:64034] Signal code:  (-6)
[fv-az1377-740:64034] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f49d8c45330]
[fv-az1377-740:64034] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f49d8c9eb2c]
[fv-az1377-740:64034] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f49d8c4527e]
[fv-az1377-740:64034] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f49d8c288ff]
[fv-az1377-740:64034] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f49d90a5ff5]
[fv-az1377-740:64034] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f49d90bb0da]
[fv-az1377-740:64034] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f49d90a5a55]
[fv-az1377-740:64034] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f49d90a5a6f]
[fv-az1377-740:64034] [ 8] plumed_master(+0x146dd)[0x56204cb466dd]
[fv-az1377-740:64034] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f49d8c2a1ca]
[fv-az1377-740:64034] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f49d8c2a28b]
[fv-az1377-740:64034] [11] plumed_master(+0x15365)[0x56204cb47365]
[fv-az1377-740:64034] *** End of error message ***
</pre>
{% endraw %}
