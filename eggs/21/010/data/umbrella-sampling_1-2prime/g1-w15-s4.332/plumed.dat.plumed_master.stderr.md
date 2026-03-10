**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w15-s4.332/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervm0kj6c:10344] *** Process received signal ***
[runnervm0kj6c:10344] Signal: Aborted (6)
[runnervm0kj6c:10344] Signal code:  (-6)
[runnervm0kj6c:10344] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f183e445330]
[runnervm0kj6c:10344] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f183e49eb2c]
[runnervm0kj6c:10344] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f183e44527e]
[runnervm0kj6c:10344] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f183e4288ff]
[runnervm0kj6c:10344] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f183e8a5ff5]
[runnervm0kj6c:10344] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f183e8bb0da]
[runnervm0kj6c:10344] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f183e8a5a55]
[runnervm0kj6c:10344] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f183e8a5a6f]
[runnervm0kj6c:10344] [ 8] plumed_master(+0x146dd)[0x55cf1954a6dd]
[runnervm0kj6c:10344] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f183e42a1ca]
[runnervm0kj6c:10344] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f183e42a28b]
[runnervm0kj6c:10344] [11] plumed_master(+0x15365)[0x55cf1954b365]
[runnervm0kj6c:10344] *** End of error message ***
</pre>
{% endraw %}
