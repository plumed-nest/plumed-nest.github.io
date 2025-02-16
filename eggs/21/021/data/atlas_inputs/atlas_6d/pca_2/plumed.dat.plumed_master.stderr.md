**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/atlas_6d/pca_2/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATLAS" is not known.
[fv-az787-589:64194] *** Process received signal ***
[fv-az787-589:64194] Signal: Aborted (6)
[fv-az787-589:64194] Signal code:  (-6)
[fv-az787-589:64194] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2160645330]
[fv-az787-589:64194] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f216069eb2c]
[fv-az787-589:64194] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f216064527e]
[fv-az787-589:64194] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f21606288ff]
[fv-az787-589:64194] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2160aa5ff5]
[fv-az787-589:64194] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2160abb0da]
[fv-az787-589:64194] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2160aa5a55]
[fv-az787-589:64194] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2160aa5a6f]
[fv-az787-589:64194] [ 8] plumed_master(+0x146dd)[0x564a65f8e6dd]
[fv-az787-589:64194] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f216062a1ca]
[fv-az787-589:64194] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f216062a28b]
[fv-az787-589:64194] [11] plumed_master(+0x15365)[0x564a65f8f365]
[fv-az787-589:64194] *** End of error message ***
</pre>
{% endraw %}
