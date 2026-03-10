**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-3/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[runnervm0kj6c:10323] *** Process received signal ***
[runnervm0kj6c:10323] Signal: Aborted (6)
[runnervm0kj6c:10323] Signal code:  (-6)
[runnervm0kj6c:10323] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb380845330]
[runnervm0kj6c:10323] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb38089eb2c]
[runnervm0kj6c:10323] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb38084527e]
[runnervm0kj6c:10323] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb3808288ff]
[runnervm0kj6c:10323] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb380ca5ff5]
[runnervm0kj6c:10323] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb380cbb0da]
[runnervm0kj6c:10323] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb380ca5a55]
[runnervm0kj6c:10323] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb380ca5a6f]
[runnervm0kj6c:10323] [ 8] plumed(+0x146dd)[0x558b215ee6dd]
[runnervm0kj6c:10323] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb38082a1ca]
[runnervm0kj6c:10323] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb38082a28b]
[runnervm0kj6c:10323] [11] plumed(+0x15365)[0x558b215ef365]
[runnervm0kj6c:10323] *** End of error message ***
</pre>
{% endraw %}
