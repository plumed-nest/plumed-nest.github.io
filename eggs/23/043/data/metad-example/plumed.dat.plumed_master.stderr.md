**Project ID:** [plumID:23.043]({{ '/' | absolute_url }}eggs/23/043/)  
Stderr for source:  metad-example/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "SPHERICAL_EXPANSION" is not known.
[runnervmgx7h7:05367] *** Process received signal ***
[runnervmgx7h7:05367] Signal: Aborted (6)
[runnervmgx7h7:05367] Signal code:  (-6)
[runnervmgx7h7:05367] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc4c1845330]
[runnervmgx7h7:05367] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc4c189ec0c]
[runnervmgx7h7:05367] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc4c184527e]
[runnervmgx7h7:05367] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc4c18288ff]
[runnervmgx7h7:05367] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc4c1ca5ff5]
[runnervmgx7h7:05367] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc4c1cbb0da]
[runnervmgx7h7:05367] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc4c1ca5a55]
[runnervmgx7h7:05367] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc4c1ca5a6f]
[runnervmgx7h7:05367] [ 8] plumed_master(+0x146dd)[0x56454e34d6dd]
[runnervmgx7h7:05367] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc4c182a1ca]
[runnervmgx7h7:05367] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc4c182a28b]
[runnervmgx7h7:05367] [11] plumed_master(+0x15365)[0x56454e34e365]
[runnervmgx7h7:05367] *** End of error message ***
</pre>
{% endraw %}
