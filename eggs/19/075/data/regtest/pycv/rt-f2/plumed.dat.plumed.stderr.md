**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-f2/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONFUNCTION" is not known.
[fv-az2207-973:12369] *** Process received signal ***
[fv-az2207-973:12369] Signal: Aborted (6)
[fv-az2207-973:12369] Signal code:  (-6)
[fv-az2207-973:12369] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7faf82645330]
[fv-az2207-973:12369] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7faf8269eb2c]
[fv-az2207-973:12369] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7faf8264527e]
[fv-az2207-973:12369] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7faf826288ff]
[fv-az2207-973:12369] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7faf82aa5ff5]
[fv-az2207-973:12369] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7faf82abb0da]
[fv-az2207-973:12369] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7faf82aa5a55]
[fv-az2207-973:12369] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7faf82aa5a6f]
[fv-az2207-973:12369] [ 8] plumed(+0x146dd)[0x556b0fa146dd]
[fv-az2207-973:12369] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7faf8262a1ca]
[fv-az2207-973:12369] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7faf8262a28b]
[fv-az2207-973:12369] [11] plumed(+0x15365)[0x556b0fa15365]
[fv-az2207-973:12369] *** End of error message ***
</pre>
{% endraw %}
