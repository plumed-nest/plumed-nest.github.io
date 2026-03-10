**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test10_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervm0kj6c:06861] *** Process received signal ***
[runnervm0kj6c:06861] Signal: Aborted (6)
[runnervm0kj6c:06861] Signal code:  (-6)
[runnervm0kj6c:06861] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7bd3a45330]
[runnervm0kj6c:06861] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7bd3a9eb2c]
[runnervm0kj6c:06861] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7bd3a4527e]
[runnervm0kj6c:06861] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7bd3a288ff]
[runnervm0kj6c:06861] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7bd3ea5ff5]
[runnervm0kj6c:06861] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7bd3ebb0da]
[runnervm0kj6c:06861] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7bd3ea5a55]
[runnervm0kj6c:06861] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7bd3ea5a6f]
[runnervm0kj6c:06861] [ 8] plumed_master(+0x146dd)[0x55f9bf8036dd]
[runnervm0kj6c:06861] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7bd3a2a1ca]
[runnervm0kj6c:06861] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7bd3a2a28b]
[runnervm0kj6c:06861] [11] plumed_master(+0x15365)[0x55f9bf804365]
[runnervm0kj6c:06861] *** End of error message ***
</pre>
{% endraw %}
