**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-2/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[fv-az2207-973:12229] *** Process received signal ***
[fv-az2207-973:12229] Signal: Aborted (6)
[fv-az2207-973:12229] Signal code:  (-6)
[fv-az2207-973:12229] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0278a45330]
[fv-az2207-973:12229] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0278a9eb2c]
[fv-az2207-973:12229] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0278a4527e]
[fv-az2207-973:12229] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0278a288ff]
[fv-az2207-973:12229] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0278ea5ff5]
[fv-az2207-973:12229] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0278ebb0da]
[fv-az2207-973:12229] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0278ea5a55]
[fv-az2207-973:12229] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0278ea5a6f]
[fv-az2207-973:12229] [ 8] plumed_master(+0x146dd)[0x559872f5f6dd]
[fv-az2207-973:12229] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0278a2a1ca]
[fv-az2207-973:12229] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0278a2a28b]
[fv-az2207-973:12229] [11] plumed_master(+0x15365)[0x559872f60365]
[fv-az2207-973:12229] *** End of error message ***
</pre>
{% endraw %}
