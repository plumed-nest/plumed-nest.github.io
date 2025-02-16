**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/atlas_6d/pca_1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATLAS" is not known.
[fv-az787-589:64127] *** Process received signal ***
[fv-az787-589:64127] Signal: Aborted (6)
[fv-az787-589:64127] Signal code:  (-6)
[fv-az787-589:64127] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f931f045330]
[fv-az787-589:64127] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f931f09eb2c]
[fv-az787-589:64127] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f931f04527e]
[fv-az787-589:64127] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f931f0288ff]
[fv-az787-589:64127] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f931f4a5ff5]
[fv-az787-589:64127] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f931f4bb0da]
[fv-az787-589:64127] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f931f4a5a55]
[fv-az787-589:64127] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f931f4a5a6f]
[fv-az787-589:64127] [ 8] plumed(+0x146dd)[0x55ce307696dd]
[fv-az787-589:64127] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f931f02a1ca]
[fv-az787-589:64127] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f931f02a28b]
[fv-az787-589:64127] [11] plumed(+0x15365)[0x55ce3076a365]
[fv-az787-589:64127] *** End of error message ***
</pre>
{% endraw %}
