**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-multi-1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[fv-az2207-973:12594] *** Process received signal ***
[fv-az2207-973:12594] Signal: Aborted (6)
[fv-az2207-973:12594] Signal code:  (-6)
[fv-az2207-973:12594] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc172845330]
[fv-az2207-973:12594] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc17289eb2c]
[fv-az2207-973:12594] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc17284527e]
[fv-az2207-973:12594] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc1728288ff]
[fv-az2207-973:12594] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc172ca5ff5]
[fv-az2207-973:12594] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc172cbb0da]
[fv-az2207-973:12594] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc172ca5a55]
[fv-az2207-973:12594] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc172ca5a6f]
[fv-az2207-973:12594] [ 8] plumed_master(+0x146dd)[0x55dc6219b6dd]
[fv-az2207-973:12594] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc17282a1ca]
[fv-az2207-973:12594] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc17282a28b]
[fv-az2207-973:12594] [11] plumed_master(+0x15365)[0x55dc6219c365]
[fv-az2207-973:12594] *** End of error message ***
</pre>
{% endraw %}
