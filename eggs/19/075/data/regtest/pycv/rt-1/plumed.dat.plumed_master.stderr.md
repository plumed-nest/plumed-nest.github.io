**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[fv-az2207-973:12179] *** Process received signal ***
[fv-az2207-973:12179] Signal: Aborted (6)
[fv-az2207-973:12179] Signal code:  (-6)
[fv-az2207-973:12179] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f63f5245330]
[fv-az2207-973:12179] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f63f529eb2c]
[fv-az2207-973:12179] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f63f524527e]
[fv-az2207-973:12179] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f63f52288ff]
[fv-az2207-973:12179] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f63f56a5ff5]
[fv-az2207-973:12179] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f63f56bb0da]
[fv-az2207-973:12179] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f63f56a5a55]
[fv-az2207-973:12179] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f63f56a5a6f]
[fv-az2207-973:12179] [ 8] plumed_master(+0x146dd)[0x563469abc6dd]
[fv-az2207-973:12179] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f63f522a1ca]
[fv-az2207-973:12179] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f63f522a28b]
[fv-az2207-973:12179] [11] plumed_master(+0x15365)[0x563469abd365]
[fv-az2207-973:12179] *** End of error message ***
</pre>
{% endraw %}
