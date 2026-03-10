**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w27-s6.924/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervm0kj6c:11017] *** Process received signal ***
[runnervm0kj6c:11017] Signal: Aborted (6)
[runnervm0kj6c:11017] Signal code:  (-6)
[runnervm0kj6c:11017] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8bb2845330]
[runnervm0kj6c:11017] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8bb289eb2c]
[runnervm0kj6c:11017] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8bb284527e]
[runnervm0kj6c:11017] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8bb28288ff]
[runnervm0kj6c:11017] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8bb2ca5ff5]
[runnervm0kj6c:11017] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8bb2cbb0da]
[runnervm0kj6c:11017] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8bb2ca5a55]
[runnervm0kj6c:11017] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8bb2ca5a6f]
[runnervm0kj6c:11017] [ 8] plumed_master(+0x146dd)[0x55b1dbf826dd]
[runnervm0kj6c:11017] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8bb282a1ca]
[runnervm0kj6c:11017] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8bb282a28b]
[runnervm0kj6c:11017] [11] plumed_master(+0x15365)[0x55b1dbf83365]
[runnervm0kj6c:11017] *** End of error message ***
</pre>
{% endraw %}
