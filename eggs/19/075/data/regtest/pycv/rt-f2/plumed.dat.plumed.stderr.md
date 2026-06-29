**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-f2/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONFUNCTION" is not known.
[runnervmmklqx:10386] *** Process received signal ***
[runnervmmklqx:10386] Signal: Aborted (6)
[runnervmmklqx:10386] Signal code:  (-6)
[runnervmmklqx:10386] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5c20845330]
[runnervmmklqx:10386] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5c2089eb2c]
[runnervmmklqx:10386] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5c2084527e]
[runnervmmklqx:10386] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5c208288ff]
[runnervmmklqx:10386] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5c20ca5ff5]
[runnervmmklqx:10386] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5c20cbb0da]
[runnervmmklqx:10386] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5c20ca5a55]
[runnervmmklqx:10386] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5c20ca5a6f]
[runnervmmklqx:10386] [ 8] plumed(+0x146dd)[0x564413bc66dd]
[runnervmmklqx:10386] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5c2082a1ca]
[runnervmmklqx:10386] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5c2082a28b]
[runnervmmklqx:10386] [11] plumed(+0x15365)[0x564413bc7365]
[runnervmmklqx:10386] *** End of error message ***
</pre>
{% endraw %}
