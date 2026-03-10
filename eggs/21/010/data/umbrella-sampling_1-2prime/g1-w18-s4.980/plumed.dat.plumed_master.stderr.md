**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w18-s4.980/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervm0kj6c:10501] *** Process received signal ***
[runnervm0kj6c:10501] Signal: Aborted (6)
[runnervm0kj6c:10501] Signal code:  (-6)
[runnervm0kj6c:10501] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f88ddc45330]
[runnervm0kj6c:10501] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f88ddc9eb2c]
[runnervm0kj6c:10501] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f88ddc4527e]
[runnervm0kj6c:10501] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f88ddc288ff]
[runnervm0kj6c:10501] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f88de0a5ff5]
[runnervm0kj6c:10501] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f88de0bb0da]
[runnervm0kj6c:10501] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f88de0a5a55]
[runnervm0kj6c:10501] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f88de0a5a6f]
[runnervm0kj6c:10501] [ 8] plumed_master(+0x146dd)[0x5635cccf26dd]
[runnervm0kj6c:10501] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f88ddc2a1ca]
[runnervm0kj6c:10501] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f88ddc2a28b]
[runnervm0kj6c:10501] [11] plumed_master(+0x15365)[0x5635cccf3365]
[runnervm0kj6c:10501] *** End of error message ***
</pre>
{% endraw %}
