**Project ID:** [plumID:21.034]({{ '/' | absolute_url }}eggs/21/034/)  
Stderr for source:  RiD/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "DEEPFE" is not known.
[runnervm0kj6c:09577] *** Process received signal ***
[runnervm0kj6c:09577] Signal: Aborted (6)
[runnervm0kj6c:09577] Signal code:  (-6)
[runnervm0kj6c:09577] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fdaa4045330]
[runnervm0kj6c:09577] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fdaa409eb2c]
[runnervm0kj6c:09577] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fdaa404527e]
[runnervm0kj6c:09577] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fdaa40288ff]
[runnervm0kj6c:09577] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fdaa44a5ff5]
[runnervm0kj6c:09577] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fdaa44bb0da]
[runnervm0kj6c:09577] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fdaa44a5a55]
[runnervm0kj6c:09577] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fdaa44a5a6f]
[runnervm0kj6c:09577] [ 8] plumed_master(+0x146dd)[0x5614ab6796dd]
[runnervm0kj6c:09577] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fdaa402a1ca]
[runnervm0kj6c:09577] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fdaa402a28b]
[runnervm0kj6c:09577] [11] plumed_master(+0x15365)[0x5614ab67a365]
[runnervm0kj6c:09577] *** End of error message ***
</pre>
{% endraw %}
