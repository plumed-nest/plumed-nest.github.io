**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/atlas_2d/pca_1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATLAS" is not known.
[fv-az1377-740:63982] *** Process received signal ***
[fv-az1377-740:63982] Signal: Aborted (6)
[fv-az1377-740:63982] Signal code:  (-6)
[fv-az1377-740:63982] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7c06045330]
[fv-az1377-740:63982] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7c0609eb2c]
[fv-az1377-740:63982] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7c0604527e]
[fv-az1377-740:63982] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7c060288ff]
[fv-az1377-740:63982] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7c064a5ff5]
[fv-az1377-740:63982] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7c064bb0da]
[fv-az1377-740:63982] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7c064a5a55]
[fv-az1377-740:63982] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7c064a5a6f]
[fv-az1377-740:63982] [ 8] plumed_master(+0x146dd)[0x55b32b8a56dd]
[fv-az1377-740:63982] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7c0602a1ca]
[fv-az1377-740:63982] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7c0602a28b]
[fv-az1377-740:63982] [11] plumed_master(+0x15365)[0x55b32b8a6365]
[fv-az1377-740:63982] *** End of error message ***
</pre>
{% endraw %}
