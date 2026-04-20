**Project ID:** [plumID:23.043]({{ '/' | absolute_url }}eggs/23/043/)  
Stderr for source:  metad-example/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "SPHERICAL_EXPANSION" is not known.
[runnervmeorf1:05593] *** Process received signal ***
[runnervmeorf1:05593] Signal: Aborted (6)
[runnervmeorf1:05593] Signal code:  (-6)
[runnervmeorf1:05593] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa86ac45330]
[runnervmeorf1:05593] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa86ac9eb2c]
[runnervmeorf1:05593] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa86ac4527e]
[runnervmeorf1:05593] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa86ac288ff]
[runnervmeorf1:05593] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa86b0a5ff5]
[runnervmeorf1:05593] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa86b0bb0da]
[runnervmeorf1:05593] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa86b0a5a55]
[runnervmeorf1:05593] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa86b0a5a6f]
[runnervmeorf1:05593] [ 8] plumed_master(+0x146dd)[0x56293c20a6dd]
[runnervmeorf1:05593] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa86ac2a1ca]
[runnervmeorf1:05593] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa86ac2a28b]
[runnervmeorf1:05593] [11] plumed_master(+0x15365)[0x56293c20b365]
[runnervmeorf1:05593] *** End of error message ***
</pre>
{% endraw %}
