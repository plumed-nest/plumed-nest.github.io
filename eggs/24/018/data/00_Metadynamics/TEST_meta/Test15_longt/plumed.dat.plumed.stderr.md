**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test15_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmgx7h7:06266] *** Process received signal ***
[runnervmgx7h7:06266] Signal: Aborted (6)
[runnervmgx7h7:06266] Signal code:  (-6)
[runnervmgx7h7:06266] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe62ba45330]
[runnervmgx7h7:06266] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe62ba9ec0c]
[runnervmgx7h7:06266] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe62ba4527e]
[runnervmgx7h7:06266] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe62ba288ff]
[runnervmgx7h7:06266] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe62bea5ff5]
[runnervmgx7h7:06266] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe62bebb0da]
[runnervmgx7h7:06266] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe62bea5a55]
[runnervmgx7h7:06266] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe62bea5a6f]
[runnervmgx7h7:06266] [ 8] plumed(+0x146dd)[0x564c8827f6dd]
[runnervmgx7h7:06266] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe62ba2a1ca]
[runnervmgx7h7:06266] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe62ba2a28b]
[runnervmgx7h7:06266] [11] plumed(+0x15365)[0x564c88280365]
[runnervmgx7h7:06266] *** End of error message ***
</pre>
{% endraw %}
