**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-3/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[pkrvmpptgkbjq6m:10769] *** Process received signal ***
[pkrvmpptgkbjq6m:10769] Signal: Aborted (6)
[pkrvmpptgkbjq6m:10769] Signal code:  (-6)
[pkrvmpptgkbjq6m:10769] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9617a45330]
[pkrvmpptgkbjq6m:10769] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9617a9eb2c]
[pkrvmpptgkbjq6m:10769] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9617a4527e]
[pkrvmpptgkbjq6m:10769] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9617a288ff]
[pkrvmpptgkbjq6m:10769] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9617ea5ff5]
[pkrvmpptgkbjq6m:10769] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9617ebb0da]
[pkrvmpptgkbjq6m:10769] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9617ea5a55]
[pkrvmpptgkbjq6m:10769] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9617ea5a6f]
[pkrvmpptgkbjq6m:10769] [ 8] plumed(+0x146dd)[0x561c643ea6dd]
[pkrvmpptgkbjq6m:10769] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9617a2a1ca]
[pkrvmpptgkbjq6m:10769] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9617a2a28b]
[pkrvmpptgkbjq6m:10769] [11] plumed(+0x15365)[0x561c643eb365]
[pkrvmpptgkbjq6m:10769] *** End of error message ***
</pre>
{% endraw %}
