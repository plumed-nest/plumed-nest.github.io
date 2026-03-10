**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w23-s6.060/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervm0kj6c:10797] *** Process received signal ***
[runnervm0kj6c:10797] Signal: Aborted (6)
[runnervm0kj6c:10797] Signal code:  (-6)
[runnervm0kj6c:10797] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f61cac45330]
[runnervm0kj6c:10797] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f61cac9eb2c]
[runnervm0kj6c:10797] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f61cac4527e]
[runnervm0kj6c:10797] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f61cac288ff]
[runnervm0kj6c:10797] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f61cb0a5ff5]
[runnervm0kj6c:10797] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f61cb0bb0da]
[runnervm0kj6c:10797] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f61cb0a5a55]
[runnervm0kj6c:10797] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f61cb0a5a6f]
[runnervm0kj6c:10797] [ 8] plumed(+0x146dd)[0x56092c1006dd]
[runnervm0kj6c:10797] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f61cac2a1ca]
[runnervm0kj6c:10797] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f61cac2a28b]
[runnervm0kj6c:10797] [11] plumed(+0x15365)[0x56092c101365]
[runnervm0kj6c:10797] *** End of error message ***
</pre>
{% endraw %}
