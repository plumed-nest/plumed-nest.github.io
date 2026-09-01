**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test14_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmgx7h7:06215] *** Process received signal ***
[runnervmgx7h7:06215] Signal: Aborted (6)
[runnervmgx7h7:06215] Signal code:  (-6)
[runnervmgx7h7:06215] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f467f845330]
[runnervmgx7h7:06215] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f467f89ec0c]
[runnervmgx7h7:06215] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f467f84527e]
[runnervmgx7h7:06215] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f467f8288ff]
[runnervmgx7h7:06215] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f467fca5ff5]
[runnervmgx7h7:06215] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f467fcbb0da]
[runnervmgx7h7:06215] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f467fca5a55]
[runnervmgx7h7:06215] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f467fca5a6f]
[runnervmgx7h7:06215] [ 8] plumed(+0x146dd)[0x556733eba6dd]
[runnervmgx7h7:06215] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f467f82a1ca]
[runnervmgx7h7:06215] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f467f82a28b]
[runnervmgx7h7:06215] [11] plumed(+0x15365)[0x556733ebb365]
[runnervmgx7h7:06215] *** End of error message ***
</pre>
{% endraw %}
