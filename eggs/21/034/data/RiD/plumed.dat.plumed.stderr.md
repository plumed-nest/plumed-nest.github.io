**Project ID:** [plumID:21.034]({{ '/' | absolute_url }}eggs/21/034/)  
Stderr for source:  RiD/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "DEEPFE" is not known.
[runnervm0kj6c:09561] *** Process received signal ***
[runnervm0kj6c:09561] Signal: Aborted (6)
[runnervm0kj6c:09561] Signal code:  (-6)
[runnervm0kj6c:09561] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f81a0c45330]
[runnervm0kj6c:09561] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f81a0c9eb2c]
[runnervm0kj6c:09561] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f81a0c4527e]
[runnervm0kj6c:09561] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f81a0c288ff]
[runnervm0kj6c:09561] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f81a10a5ff5]
[runnervm0kj6c:09561] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f81a10bb0da]
[runnervm0kj6c:09561] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f81a10a5a55]
[runnervm0kj6c:09561] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f81a10a5a6f]
[runnervm0kj6c:09561] [ 8] plumed(+0x146dd)[0x5566df1766dd]
[runnervm0kj6c:09561] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f81a0c2a1ca]
[runnervm0kj6c:09561] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f81a0c2a28b]
[runnervm0kj6c:09561] [11] plumed(+0x15365)[0x5566df177365]
[runnervm0kj6c:09561] *** End of error message ***
</pre>
{% endraw %}
