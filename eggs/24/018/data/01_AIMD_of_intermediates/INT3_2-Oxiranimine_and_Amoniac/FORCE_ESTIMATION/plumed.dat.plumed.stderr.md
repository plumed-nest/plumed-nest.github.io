**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  01_AIMD_of_intermediates/INT3_2-Oxiranimine_and_Amoniac/FORCE_ESTIMATION/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az787-589:61666] *** Process received signal ***
[fv-az787-589:61666] Signal: Aborted (6)
[fv-az787-589:61666] Signal code:  (-6)
[fv-az787-589:61666] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbf56045330]
[fv-az787-589:61666] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbf5609eb2c]
[fv-az787-589:61666] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbf5604527e]
[fv-az787-589:61666] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbf560288ff]
[fv-az787-589:61666] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbf564a5ff5]
[fv-az787-589:61666] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbf564bb0da]
[fv-az787-589:61666] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbf564a5a55]
[fv-az787-589:61666] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbf564a5a6f]
[fv-az787-589:61666] [ 8] plumed(+0x146dd)[0x55857ee5f6dd]
[fv-az787-589:61666] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbf5602a1ca]
[fv-az787-589:61666] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbf5602a28b]
[fv-az787-589:61666] [11] plumed(+0x15365)[0x55857ee60365]
[fv-az787-589:61666] *** End of error message ***
</pre>
{% endraw %}
