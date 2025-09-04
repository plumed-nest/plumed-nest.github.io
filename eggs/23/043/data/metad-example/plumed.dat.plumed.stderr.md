**Project ID:** [plumID:23.043]({{ '/' | absolute_url }}eggs/23/043/)  
Stderr for source:  metad-example/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "SPHERICAL_EXPANSION" is not known.
[pkrvm7jw40e0xgp:07360] *** Process received signal ***
[pkrvm7jw40e0xgp:07360] Signal: Aborted (6)
[pkrvm7jw40e0xgp:07360] Signal code:  (-6)
[pkrvm7jw40e0xgp:07360] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd048645330]
[pkrvm7jw40e0xgp:07360] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd04869eb2c]
[pkrvm7jw40e0xgp:07360] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd04864527e]
[pkrvm7jw40e0xgp:07360] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd0486288ff]
[pkrvm7jw40e0xgp:07360] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd048aa5ff5]
[pkrvm7jw40e0xgp:07360] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd048abb0da]
[pkrvm7jw40e0xgp:07360] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd048aa5a55]
[pkrvm7jw40e0xgp:07360] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd048aa5a6f]
[pkrvm7jw40e0xgp:07360] [ 8] plumed(+0x146dd)[0x5596d73f46dd]
[pkrvm7jw40e0xgp:07360] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd04862a1ca]
[pkrvm7jw40e0xgp:07360] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd04862a28b]
[pkrvm7jw40e0xgp:07360] [11] plumed(+0x15365)[0x5596d73f5365]
[pkrvm7jw40e0xgp:07360] *** End of error message ***
</pre>
{% endraw %}
