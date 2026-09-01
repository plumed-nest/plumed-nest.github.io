**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[runnervmgx7h7:09676] *** Process received signal ***
[runnervmgx7h7:09676] Signal: Aborted (6)
[runnervmgx7h7:09676] Signal code:  (-6)
[runnervmgx7h7:09676] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe7e2c45330]
[runnervmgx7h7:09676] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe7e2c9ec0c]
[runnervmgx7h7:09676] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe7e2c4527e]
[runnervmgx7h7:09676] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe7e2c288ff]
[runnervmgx7h7:09676] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe7e30a5ff5]
[runnervmgx7h7:09676] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe7e30bb0da]
[runnervmgx7h7:09676] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe7e30a5a55]
[runnervmgx7h7:09676] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe7e30a5a6f]
[runnervmgx7h7:09676] [ 8] plumed(+0x146dd)[0x557c5c2436dd]
[runnervmgx7h7:09676] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe7e2c2a1ca]
[runnervmgx7h7:09676] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe7e2c2a28b]
[runnervmgx7h7:09676] [11] plumed(+0x15365)[0x557c5c244365]
[runnervmgx7h7:09676] *** End of error message ***
</pre>
{% endraw %}
