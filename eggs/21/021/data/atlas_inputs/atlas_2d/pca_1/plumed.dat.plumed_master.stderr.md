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
[fv-az1720-841:08810] *** Process received signal ***
[fv-az1720-841:08810] Signal: Aborted (6)
[fv-az1720-841:08810] Signal code:  (-6)
[fv-az1720-841:08810] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fdd1d845330]
[fv-az1720-841:08810] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fdd1d89eb2c]
[fv-az1720-841:08810] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fdd1d84527e]
[fv-az1720-841:08810] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fdd1d8288ff]
[fv-az1720-841:08810] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fdd1dca5ff5]
[fv-az1720-841:08810] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fdd1dcbb0da]
[fv-az1720-841:08810] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fdd1dca5a55]
[fv-az1720-841:08810] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fdd1dca5a6f]
[fv-az1720-841:08810] [ 8] plumed_master(+0x146dd)[0x564124a556dd]
[fv-az1720-841:08810] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fdd1d82a1ca]
[fv-az1720-841:08810] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fdd1d82a28b]
[fv-az1720-841:08810] [11] plumed_master(+0x15365)[0x564124a56365]
[fv-az1720-841:08810] *** End of error message ***
</pre>
{% endraw %}
