**Project ID:** [plumID:19.026]({{ '/' | absolute_url }}eggs/19/026/)  
Stderr for source:  EXAMPLE/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HBOND_COORD" is not known.
[pkrvmpptgkbjq6m:12806] *** Process received signal ***
[pkrvmpptgkbjq6m:12806] Signal: Aborted (6)
[pkrvmpptgkbjq6m:12806] Signal code:  (-6)
[pkrvmpptgkbjq6m:12806] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8620045330]
[pkrvmpptgkbjq6m:12806] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f862009eb2c]
[pkrvmpptgkbjq6m:12806] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f862004527e]
[pkrvmpptgkbjq6m:12806] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f86200288ff]
[pkrvmpptgkbjq6m:12806] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f86204a5ff5]
[pkrvmpptgkbjq6m:12806] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f86204bb0da]
[pkrvmpptgkbjq6m:12806] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f86204a5a55]
[pkrvmpptgkbjq6m:12806] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f86204a5a6f]
[pkrvmpptgkbjq6m:12806] [ 8] plumed(+0x146dd)[0x55c3a1ca36dd]
[pkrvmpptgkbjq6m:12806] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f862002a1ca]
[pkrvmpptgkbjq6m:12806] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f862002a28b]
[pkrvmpptgkbjq6m:12806] [11] plumed(+0x15365)[0x55c3a1ca4365]
[pkrvmpptgkbjq6m:12806] *** End of error message ***
</pre>
{% endraw %}
