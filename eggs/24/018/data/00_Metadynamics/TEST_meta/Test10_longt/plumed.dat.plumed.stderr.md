**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test10_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmgx7h7:06011] *** Process received signal ***
[runnervmgx7h7:06011] Signal: Aborted (6)
[runnervmgx7h7:06011] Signal code:  (-6)
[runnervmgx7h7:06011] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f45b3a45330]
[runnervmgx7h7:06011] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f45b3a9ec0c]
[runnervmgx7h7:06011] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f45b3a4527e]
[runnervmgx7h7:06011] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f45b3a288ff]
[runnervmgx7h7:06011] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f45b3ea5ff5]
[runnervmgx7h7:06011] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f45b3ebb0da]
[runnervmgx7h7:06011] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f45b3ea5a55]
[runnervmgx7h7:06011] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f45b3ea5a6f]
[runnervmgx7h7:06011] [ 8] plumed(+0x146dd)[0x55b6e04016dd]
[runnervmgx7h7:06011] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f45b3a2a1ca]
[runnervmgx7h7:06011] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f45b3a2a28b]
[runnervmgx7h7:06011] [11] plumed(+0x15365)[0x55b6e0402365]
[runnervmgx7h7:06011] *** End of error message ***
</pre>
{% endraw %}
