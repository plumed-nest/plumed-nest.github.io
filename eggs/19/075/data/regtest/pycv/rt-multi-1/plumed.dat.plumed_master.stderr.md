**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-multi-1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[runnervm0kj6c:10646] *** Process received signal ***
[runnervm0kj6c:10646] Signal: Aborted (6)
[runnervm0kj6c:10646] Signal code:  (-6)
[runnervm0kj6c:10646] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5c9c845330]
[runnervm0kj6c:10646] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5c9c89eb2c]
[runnervm0kj6c:10646] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5c9c84527e]
[runnervm0kj6c:10646] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5c9c8288ff]
[runnervm0kj6c:10646] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5c9cca5ff5]
[runnervm0kj6c:10646] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5c9ccbb0da]
[runnervm0kj6c:10646] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5c9cca5a55]
[runnervm0kj6c:10646] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5c9cca5a6f]
[runnervm0kj6c:10646] [ 8] plumed_master(+0x146dd)[0x557c9768a6dd]
[runnervm0kj6c:10646] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5c9c82a1ca]
[runnervm0kj6c:10646] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5c9c82a28b]
[runnervm0kj6c:10646] [11] plumed_master(+0x15365)[0x557c9768b365]
[runnervm0kj6c:10646] *** End of error message ***
</pre>
{% endraw %}
