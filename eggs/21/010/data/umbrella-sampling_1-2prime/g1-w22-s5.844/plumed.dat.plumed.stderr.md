**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w22-s5.844/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervm0kj6c:10746] *** Process received signal ***
[runnervm0kj6c:10746] Signal: Aborted (6)
[runnervm0kj6c:10746] Signal code:  (-6)
[runnervm0kj6c:10746] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ffa13a45330]
[runnervm0kj6c:10746] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ffa13a9eb2c]
[runnervm0kj6c:10746] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ffa13a4527e]
[runnervm0kj6c:10746] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ffa13a288ff]
[runnervm0kj6c:10746] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ffa13ea5ff5]
[runnervm0kj6c:10746] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ffa13ebb0da]
[runnervm0kj6c:10746] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ffa13ea5a55]
[runnervm0kj6c:10746] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ffa13ea5a6f]
[runnervm0kj6c:10746] [ 8] plumed(+0x146dd)[0x5653f65f66dd]
[runnervm0kj6c:10746] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ffa13a2a1ca]
[runnervm0kj6c:10746] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ffa13a2a28b]
[runnervm0kj6c:10746] [11] plumed(+0x15365)[0x5653f65f7365]
[runnervm0kj6c:10746] *** End of error message ***
</pre>
{% endraw %}
