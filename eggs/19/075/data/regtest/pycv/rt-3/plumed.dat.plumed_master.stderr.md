**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-3/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[runnervm0kj6c:10338] *** Process received signal ***
[runnervm0kj6c:10338] Signal: Aborted (6)
[runnervm0kj6c:10338] Signal code:  (-6)
[runnervm0kj6c:10338] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1a20245330]
[runnervm0kj6c:10338] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1a2029eb2c]
[runnervm0kj6c:10338] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1a2024527e]
[runnervm0kj6c:10338] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1a202288ff]
[runnervm0kj6c:10338] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1a206a5ff5]
[runnervm0kj6c:10338] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1a206bb0da]
[runnervm0kj6c:10338] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1a206a5a55]
[runnervm0kj6c:10338] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1a206a5a6f]
[runnervm0kj6c:10338] [ 8] plumed_master(+0x146dd)[0x55b0ee16d6dd]
[runnervm0kj6c:10338] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1a2022a1ca]
[runnervm0kj6c:10338] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1a2022a28b]
[runnervm0kj6c:10338] [11] plumed_master(+0x15365)[0x55b0ee16e365]
[runnervm0kj6c:10338] *** End of error message ***
</pre>
{% endraw %}
