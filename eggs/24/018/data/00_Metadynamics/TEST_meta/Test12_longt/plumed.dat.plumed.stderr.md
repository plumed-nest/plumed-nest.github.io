**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test12_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmgx7h7:06113] *** Process received signal ***
[runnervmgx7h7:06113] Signal: Aborted (6)
[runnervmgx7h7:06113] Signal code:  (-6)
[runnervmgx7h7:06113] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0f44245330]
[runnervmgx7h7:06113] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0f4429ec0c]
[runnervmgx7h7:06113] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0f4424527e]
[runnervmgx7h7:06113] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0f442288ff]
[runnervmgx7h7:06113] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0f446a5ff5]
[runnervmgx7h7:06113] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0f446bb0da]
[runnervmgx7h7:06113] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0f446a5a55]
[runnervmgx7h7:06113] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0f446a5a6f]
[runnervmgx7h7:06113] [ 8] plumed(+0x146dd)[0x55ae733716dd]
[runnervmgx7h7:06113] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0f4422a1ca]
[runnervmgx7h7:06113] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0f4422a28b]
[runnervmgx7h7:06113] [11] plumed(+0x15365)[0x55ae73372365]
[runnervmgx7h7:06113] *** End of error message ***
</pre>
{% endraw %}
