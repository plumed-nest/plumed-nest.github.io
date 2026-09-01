**Project ID:** [plumID:23.043]({{ '/' | absolute_url }}eggs/23/043/)  
Stderr for source:  metad-example/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "SPHERICAL_EXPANSION" is not known.
[runnervmgx7h7:05352] *** Process received signal ***
[runnervmgx7h7:05352] Signal: Aborted (6)
[runnervmgx7h7:05352] Signal code:  (-6)
[runnervmgx7h7:05352] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9f84845330]
[runnervmgx7h7:05352] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9f8489ec0c]
[runnervmgx7h7:05352] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9f8484527e]
[runnervmgx7h7:05352] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9f848288ff]
[runnervmgx7h7:05352] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9f84ca5ff5]
[runnervmgx7h7:05352] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9f84cbb0da]
[runnervmgx7h7:05352] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9f84ca5a55]
[runnervmgx7h7:05352] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9f84ca5a6f]
[runnervmgx7h7:05352] [ 8] plumed(+0x146dd)[0x55b1f62766dd]
[runnervmgx7h7:05352] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9f8482a1ca]
[runnervmgx7h7:05352] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9f8482a28b]
[runnervmgx7h7:05352] [11] plumed(+0x15365)[0x55b1f6277365]
[runnervmgx7h7:05352] *** End of error message ***
</pre>
{% endraw %}
