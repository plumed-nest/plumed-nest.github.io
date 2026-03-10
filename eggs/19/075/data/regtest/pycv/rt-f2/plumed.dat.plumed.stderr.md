**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-f2/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONFUNCTION" is not known.
[runnervm0kj6c:10426] *** Process received signal ***
[runnervm0kj6c:10426] Signal: Aborted (6)
[runnervm0kj6c:10426] Signal code:  (-6)
[runnervm0kj6c:10426] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd27d445330]
[runnervm0kj6c:10426] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd27d49eb2c]
[runnervm0kj6c:10426] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd27d44527e]
[runnervm0kj6c:10426] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd27d4288ff]
[runnervm0kj6c:10426] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd27d8a5ff5]
[runnervm0kj6c:10426] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd27d8bb0da]
[runnervm0kj6c:10426] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd27d8a5a55]
[runnervm0kj6c:10426] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd27d8a5a6f]
[runnervm0kj6c:10426] [ 8] plumed(+0x146dd)[0x5569372096dd]
[runnervm0kj6c:10426] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd27d42a1ca]
[runnervm0kj6c:10426] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd27d42a28b]
[runnervm0kj6c:10426] [11] plumed(+0x15365)[0x55693720a365]
[runnervm0kj6c:10426] *** End of error message ***
</pre>
{% endraw %}
