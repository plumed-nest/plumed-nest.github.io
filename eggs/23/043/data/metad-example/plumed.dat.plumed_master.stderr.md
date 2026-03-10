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
[runnervm0kj6c:05174] *** Process received signal ***
[runnervm0kj6c:05174] Signal: Aborted (6)
[runnervm0kj6c:05174] Signal code:  (-6)
[runnervm0kj6c:05174] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc0c0045330]
[runnervm0kj6c:05174] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc0c009eb2c]
[runnervm0kj6c:05174] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc0c004527e]
[runnervm0kj6c:05174] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc0c00288ff]
[runnervm0kj6c:05174] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc0c04a5ff5]
[runnervm0kj6c:05174] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc0c04bb0da]
[runnervm0kj6c:05174] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc0c04a5a55]
[runnervm0kj6c:05174] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc0c04a5a6f]
[runnervm0kj6c:05174] [ 8] plumed_master(+0x146dd)[0x5630fdde96dd]
[runnervm0kj6c:05174] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc0c002a1ca]
[runnervm0kj6c:05174] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc0c002a28b]
[runnervm0kj6c:05174] [11] plumed_master(+0x15365)[0x5630fddea365]
[runnervm0kj6c:05174] *** End of error message ***
</pre>
{% endraw %}
