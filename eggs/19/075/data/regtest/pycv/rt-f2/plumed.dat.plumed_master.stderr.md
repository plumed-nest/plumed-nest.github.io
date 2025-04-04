**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-f2/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONFUNCTION" is not known.
[fv-az2207-973:12385] *** Process received signal ***
[fv-az2207-973:12385] Signal: Aborted (6)
[fv-az2207-973:12385] Signal code:  (-6)
[fv-az2207-973:12385] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f66abe45330]
[fv-az2207-973:12385] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f66abe9eb2c]
[fv-az2207-973:12385] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f66abe4527e]
[fv-az2207-973:12385] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f66abe288ff]
[fv-az2207-973:12385] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f66ac2a5ff5]
[fv-az2207-973:12385] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f66ac2bb0da]
[fv-az2207-973:12385] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f66ac2a5a55]
[fv-az2207-973:12385] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f66ac2a5a6f]
[fv-az2207-973:12385] [ 8] plumed_master(+0x146dd)[0x561bc693f6dd]
[fv-az2207-973:12385] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f66abe2a1ca]
[fv-az2207-973:12385] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f66abe2a28b]
[fv-az2207-973:12385] [11] plumed_master(+0x15365)[0x561bc6940365]
[fv-az2207-973:12385] *** End of error message ***
</pre>
{% endraw %}
