**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  01_AIMD_of_intermediates/INT3_2-Oxiranimine_and_Amoniac/FORCE_ESTIMATION/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervm0kj6c:07743] *** Process received signal ***
[runnervm0kj6c:07743] Signal: Aborted (6)
[runnervm0kj6c:07743] Signal code:  (-6)
[runnervm0kj6c:07743] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f45e9445330]
[runnervm0kj6c:07743] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f45e949eb2c]
[runnervm0kj6c:07743] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f45e944527e]
[runnervm0kj6c:07743] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f45e94288ff]
[runnervm0kj6c:07743] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f45e98a5ff5]
[runnervm0kj6c:07743] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f45e98bb0da]
[runnervm0kj6c:07743] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f45e98a5a55]
[runnervm0kj6c:07743] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f45e98a5a6f]
[runnervm0kj6c:07743] [ 8] plumed_master(+0x146dd)[0x558b7c2306dd]
[runnervm0kj6c:07743] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f45e942a1ca]
[runnervm0kj6c:07743] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f45e942a28b]
[runnervm0kj6c:07743] [11] plumed_master(+0x15365)[0x558b7c231365]
[runnervm0kj6c:07743] *** End of error message ***
</pre>
{% endraw %}
