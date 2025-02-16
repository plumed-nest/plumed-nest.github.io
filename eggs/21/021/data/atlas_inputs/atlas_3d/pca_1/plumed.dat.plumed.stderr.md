**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/atlas_3d/pca_1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATLAS" is not known.
[fv-az787-589:63972] *** Process received signal ***
[fv-az787-589:63972] Signal: Aborted (6)
[fv-az787-589:63972] Signal code:  (-6)
[fv-az787-589:63972] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fab77245330]
[fv-az787-589:63972] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fab7729eb2c]
[fv-az787-589:63972] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fab7724527e]
[fv-az787-589:63972] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fab772288ff]
[fv-az787-589:63972] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fab776a5ff5]
[fv-az787-589:63972] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fab776bb0da]
[fv-az787-589:63972] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fab776a5a55]
[fv-az787-589:63972] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fab776a5a6f]
[fv-az787-589:63972] [ 8] plumed(+0x146dd)[0x564321ecf6dd]
[fv-az787-589:63972] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fab7722a1ca]
[fv-az787-589:63972] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fab7722a28b]
[fv-az787-589:63972] [11] plumed(+0x15365)[0x564321ed0365]
[fv-az787-589:63972] *** End of error message ***
</pre>
{% endraw %}
