**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/LJ-38/plumed_biased.dat   
Download: [zipped raw stdout](plumed_biased.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_biased.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATLAS" is not known.
[fv-az787-589:63813] *** Process received signal ***
[fv-az787-589:63813] Signal: Aborted (6)
[fv-az787-589:63813] Signal code:  (-6)
[fv-az787-589:63813] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd919845330]
[fv-az787-589:63813] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd91989eb2c]
[fv-az787-589:63813] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd91984527e]
[fv-az787-589:63813] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd9198288ff]
[fv-az787-589:63813] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd919ca5ff5]
[fv-az787-589:63813] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd919cbb0da]
[fv-az787-589:63813] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd919ca5a55]
[fv-az787-589:63813] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd919ca5a6f]
[fv-az787-589:63813] [ 8] plumed(+0x146dd)[0x557ce0f286dd]
[fv-az787-589:63813] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd91982a1ca]
[fv-az787-589:63813] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd91982a28b]
[fv-az787-589:63813] [11] plumed(+0x15365)[0x557ce0f29365]
[fv-az787-589:63813] *** End of error message ***
</pre>
{% endraw %}
