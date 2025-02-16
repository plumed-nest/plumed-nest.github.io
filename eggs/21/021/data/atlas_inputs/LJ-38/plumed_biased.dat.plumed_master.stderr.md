**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/LJ-38/plumed_biased.dat   
Download: [zipped raw stdout](plumed_biased.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_biased.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATLAS" is not known.
[fv-az787-589:63830] *** Process received signal ***
[fv-az787-589:63830] Signal: Aborted (6)
[fv-az787-589:63830] Signal code:  (-6)
[fv-az787-589:63830] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fcaa2a45330]
[fv-az787-589:63830] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fcaa2a9eb2c]
[fv-az787-589:63830] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fcaa2a4527e]
[fv-az787-589:63830] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fcaa2a288ff]
[fv-az787-589:63830] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fcaa2ea5ff5]
[fv-az787-589:63830] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fcaa2ebb0da]
[fv-az787-589:63830] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fcaa2ea5a55]
[fv-az787-589:63830] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fcaa2ea5a6f]
[fv-az787-589:63830] [ 8] plumed_master(+0x146dd)[0x55f6287cb6dd]
[fv-az787-589:63830] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fcaa2a2a1ca]
[fv-az787-589:63830] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fcaa2a2a28b]
[fv-az787-589:63830] [11] plumed_master(+0x15365)[0x55f6287cc365]
[fv-az787-589:63830] *** End of error message ***
</pre>
{% endraw %}
