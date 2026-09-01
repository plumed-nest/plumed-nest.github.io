**Project ID:** [plumID:21.034]({{ '/' | absolute_url }}eggs/21/034/)  
Stderr for source:  RiD/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "DEEPFE" is not known.
[runnervmgx7h7:06553] *** Process received signal ***
[runnervmgx7h7:06553] Signal: Aborted (6)
[runnervmgx7h7:06553] Signal code:  (-6)
[runnervmgx7h7:06553] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fda4f245330]
[runnervmgx7h7:06553] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fda4f29ec0c]
[runnervmgx7h7:06553] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fda4f24527e]
[runnervmgx7h7:06553] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fda4f2288ff]
[runnervmgx7h7:06553] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fda4f6a5ff5]
[runnervmgx7h7:06553] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fda4f6bb0da]
[runnervmgx7h7:06553] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fda4f6a5a55]
[runnervmgx7h7:06553] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fda4f6a5a6f]
[runnervmgx7h7:06553] [ 8] plumed_master(+0x146dd)[0x55b81b2c36dd]
[runnervmgx7h7:06553] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fda4f22a1ca]
[runnervmgx7h7:06553] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fda4f22a28b]
[runnervmgx7h7:06553] [11] plumed_master(+0x15365)[0x55b81b2c4365]
[runnervmgx7h7:06553] *** End of error message ***
</pre>
{% endraw %}
