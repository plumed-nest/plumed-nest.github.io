**Project ID:** [plumID:25.030]({{ '/' | absolute_url }}eggs/25/030/)  
Stderr for source:  plumed_pulling.dat   
Download: [zipped raw stdout](plumed_pulling.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_pulling.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[runnervm0kj6c:04775] *** Process received signal ***
[runnervm0kj6c:04775] Signal: Aborted (6)
[runnervm0kj6c:04775] Signal code:  (-6)
[runnervm0kj6c:04775] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbc17645330]
[runnervm0kj6c:04775] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbc1769eb2c]
[runnervm0kj6c:04775] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbc1764527e]
[runnervm0kj6c:04775] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbc176288ff]
[runnervm0kj6c:04775] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbc17aa5ff5]
[runnervm0kj6c:04775] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbc17abb0da]
[runnervm0kj6c:04775] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbc17aa5a55]
[runnervm0kj6c:04775] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbc17aa5a6f]
[runnervm0kj6c:04775] [ 8] plumed_master(+0x146dd)[0x55c6ae5d56dd]
[runnervm0kj6c:04775] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbc1762a1ca]
[runnervm0kj6c:04775] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbc1762a28b]
[runnervm0kj6c:04775] [11] plumed_master(+0x15365)[0x55c6ae5d6365]
[runnervm0kj6c:04775] *** End of error message ***
</pre>
{% endraw %}
