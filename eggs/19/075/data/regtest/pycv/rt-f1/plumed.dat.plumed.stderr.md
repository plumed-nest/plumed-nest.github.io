**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-f1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONFUNCTION" is not known.
[fv-az2207-973:12317] *** Process received signal ***
[fv-az2207-973:12317] Signal: Aborted (6)
[fv-az2207-973:12317] Signal code:  (-6)
[fv-az2207-973:12317] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fda93845330]
[fv-az2207-973:12317] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fda9389eb2c]
[fv-az2207-973:12317] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fda9384527e]
[fv-az2207-973:12317] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fda938288ff]
[fv-az2207-973:12317] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fda93ca5ff5]
[fv-az2207-973:12317] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fda93cbb0da]
[fv-az2207-973:12317] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fda93ca5a55]
[fv-az2207-973:12317] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fda93ca5a6f]
[fv-az2207-973:12317] [ 8] plumed(+0x146dd)[0x5592394546dd]
[fv-az2207-973:12317] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fda9382a1ca]
[fv-az2207-973:12317] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fda9382a28b]
[fv-az2207-973:12317] [11] plumed(+0x15365)[0x559239455365]
[fv-az2207-973:12317] *** End of error message ***
</pre>
{% endraw %}
