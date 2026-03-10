**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  01_AIMD_of_intermediates/INT2_NEW/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervm0kj6c:07571] *** Process received signal ***
[runnervm0kj6c:07571] Signal: Aborted (6)
[runnervm0kj6c:07571] Signal code:  (-6)
[runnervm0kj6c:07571] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff5c2245330]
[runnervm0kj6c:07571] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff5c229eb2c]
[runnervm0kj6c:07571] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff5c224527e]
[runnervm0kj6c:07571] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff5c22288ff]
[runnervm0kj6c:07571] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff5c26a5ff5]
[runnervm0kj6c:07571] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff5c26bb0da]
[runnervm0kj6c:07571] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff5c26a5a55]
[runnervm0kj6c:07571] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff5c26a5a6f]
[runnervm0kj6c:07571] [ 8] plumed(+0x146dd)[0x55c9113f46dd]
[runnervm0kj6c:07571] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff5c222a1ca]
[runnervm0kj6c:07571] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff5c222a28b]
[runnervm0kj6c:07571] [11] plumed(+0x15365)[0x55c9113f5365]
[runnervm0kj6c:07571] *** End of error message ***
</pre>
{% endraw %}
