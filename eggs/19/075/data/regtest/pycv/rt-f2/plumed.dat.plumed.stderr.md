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
[runnervmkj6or:11415] *** Process received signal ***
[runnervmkj6or:11415] Signal: Aborted (6)
[runnervmkj6or:11415] Signal code:  (-6)
[runnervmkj6or:11415] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f19e2c45330]
[runnervmkj6or:11415] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f19e2c9eb2c]
[runnervmkj6or:11415] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f19e2c4527e]
[runnervmkj6or:11415] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f19e2c288ff]
[runnervmkj6or:11415] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f19e30a5ff5]
[runnervmkj6or:11415] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f19e30bb0da]
[runnervmkj6or:11415] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f19e30a5a55]
[runnervmkj6or:11415] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f19e30a5a6f]
[runnervmkj6or:11415] [ 8] plumed(+0x146dd)[0x5555fb4296dd]
[runnervmkj6or:11415] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f19e2c2a1ca]
[runnervmkj6or:11415] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f19e2c2a28b]
[runnervmkj6or:11415] [11] plumed(+0x15365)[0x5555fb42a365]
[runnervmkj6or:11415] *** End of error message ***
</pre>
{% endraw %}
