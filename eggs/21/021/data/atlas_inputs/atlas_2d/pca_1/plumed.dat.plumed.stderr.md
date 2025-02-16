**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/atlas_2d/pca_1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATLAS" is not known.
[fv-az787-589:63867] *** Process received signal ***
[fv-az787-589:63867] Signal: Aborted (6)
[fv-az787-589:63867] Signal code:  (-6)
[fv-az787-589:63867] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff3fe245330]
[fv-az787-589:63867] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff3fe29eb2c]
[fv-az787-589:63867] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff3fe24527e]
[fv-az787-589:63867] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff3fe2288ff]
[fv-az787-589:63867] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff3fe6a5ff5]
[fv-az787-589:63867] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff3fe6bb0da]
[fv-az787-589:63867] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff3fe6a5a55]
[fv-az787-589:63867] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff3fe6a5a6f]
[fv-az787-589:63867] [ 8] plumed(+0x146dd)[0x55ed1d8a56dd]
[fv-az787-589:63867] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff3fe22a1ca]
[fv-az787-589:63867] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff3fe22a28b]
[fv-az787-589:63867] [11] plumed(+0x15365)[0x55ed1d8a6365]
[fv-az787-589:63867] *** End of error message ***
</pre>
{% endraw %}
