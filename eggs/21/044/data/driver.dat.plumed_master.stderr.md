**Project ID:** [plumID:21.044]({{ '/' | absolute_url }}eggs/21/044/)  
Stderr for source:  driver.dat   
Download: [zipped raw stdout](driver.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](driver.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'std::out_of_range'
what():  map::at
[runnervm0kj6c:07793] *** Process received signal ***
[runnervm0kj6c:07793] Signal: Aborted (6)
[runnervm0kj6c:07793] Signal code:  (-6)
[runnervm0kj6c:07793] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f620c245330]
[runnervm0kj6c:07793] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f620c29eb2c]
[runnervm0kj6c:07793] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f620c24527e]
[runnervm0kj6c:07793] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f620c2288ff]
[runnervm0kj6c:07793] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f620c6a5ff5]
[runnervm0kj6c:07793] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f620c6bb0da]
[runnervm0kj6c:07793] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f620c6a5a55]
[runnervm0kj6c:07793] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f620c6a5a6f]
[runnervm0kj6c:07793] [ 8] plumed_master(+0x146dd)[0x55b3998356dd]
[runnervm0kj6c:07793] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f620c22a1ca]
[runnervm0kj6c:07793] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f620c22a28b]
[runnervm0kj6c:07793] [11] plumed_master(+0x15365)[0x55b399836365]
[runnervm0kj6c:07793] *** End of error message ***
</pre>
{% endraw %}
