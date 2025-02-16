**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  01_AIMD_of_intermediates/INT3_2-Oxiranimine_and_Amoniac/FORCE_ESTIMATION/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az787-589:61682] *** Process received signal ***
[fv-az787-589:61682] Signal: Aborted (6)
[fv-az787-589:61682] Signal code:  (-6)
[fv-az787-589:61682] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1834e45330]
[fv-az787-589:61682] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1834e9eb2c]
[fv-az787-589:61682] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1834e4527e]
[fv-az787-589:61682] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1834e288ff]
[fv-az787-589:61682] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f18352a5ff5]
[fv-az787-589:61682] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f18352bb0da]
[fv-az787-589:61682] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f18352a5a55]
[fv-az787-589:61682] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f18352a5a6f]
[fv-az787-589:61682] [ 8] plumed_master(+0x146dd)[0x55dd202f26dd]
[fv-az787-589:61682] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1834e2a1ca]
[fv-az787-589:61682] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1834e2a28b]
[fv-az787-589:61682] [11] plumed_master(+0x15365)[0x55dd202f3365]
[fv-az787-589:61682] *** End of error message ***
</pre>
{% endraw %}
