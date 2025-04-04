**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-2/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[fv-az2207-973:12214] *** Process received signal ***
[fv-az2207-973:12214] Signal: Aborted (6)
[fv-az2207-973:12214] Signal code:  (-6)
[fv-az2207-973:12214] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2dc6045330]
[fv-az2207-973:12214] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2dc609eb2c]
[fv-az2207-973:12214] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2dc604527e]
[fv-az2207-973:12214] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2dc60288ff]
[fv-az2207-973:12214] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2dc64a5ff5]
[fv-az2207-973:12214] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2dc64bb0da]
[fv-az2207-973:12214] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2dc64a5a55]
[fv-az2207-973:12214] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2dc64a5a6f]
[fv-az2207-973:12214] [ 8] plumed(+0x146dd)[0x5638b274b6dd]
[fv-az2207-973:12214] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2dc602a1ca]
[fv-az2207-973:12214] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2dc602a28b]
[fv-az2207-973:12214] [11] plumed(+0x15365)[0x5638b274c365]
[fv-az2207-973:12214] *** End of error message ***
</pre>
{% endraw %}
