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
[fv-az2207-973:12266] *** Process received signal ***
[fv-az2207-973:12266] Signal: Aborted (6)
[fv-az2207-973:12266] Signal code:  (-6)
[fv-az2207-973:12266] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8dbe445330]
[fv-az2207-973:12266] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8dbe49eb2c]
[fv-az2207-973:12266] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8dbe44527e]
[fv-az2207-973:12266] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8dbe4288ff]
[fv-az2207-973:12266] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8dbe8a5ff5]
[fv-az2207-973:12266] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8dbe8bb0da]
[fv-az2207-973:12266] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8dbe8a5a55]
[fv-az2207-973:12266] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8dbe8a5a6f]
[fv-az2207-973:12266] [ 8] plumed(+0x146dd)[0x560c679ed6dd]
[fv-az2207-973:12266] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8dbe42a1ca]
[fv-az2207-973:12266] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8dbe42a28b]
[fv-az2207-973:12266] [11] plumed(+0x15365)[0x560c679ee365]
[fv-az2207-973:12266] *** End of error message ***
</pre>
{% endraw %}
