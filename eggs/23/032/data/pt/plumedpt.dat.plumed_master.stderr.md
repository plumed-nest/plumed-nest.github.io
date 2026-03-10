**Project ID:** [plumID:23.032]({{ '/' | absolute_url }}eggs/23/032/)  
Stderr for source:  pt/plumedpt.dat   
Download: [zipped raw stdout](plumedpt.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumedpt.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTORCH_MODEL_CV" is not known.
[runnervm0kj6c:08177] *** Process received signal ***
[runnervm0kj6c:08177] Signal: Aborted (6)
[runnervm0kj6c:08177] Signal code:  (-6)
[runnervm0kj6c:08177] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fda64a45330]
[runnervm0kj6c:08177] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fda64a9eb2c]
[runnervm0kj6c:08177] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fda64a4527e]
[runnervm0kj6c:08177] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fda64a288ff]
[runnervm0kj6c:08177] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fda64ea5ff5]
[runnervm0kj6c:08177] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fda64ebb0da]
[runnervm0kj6c:08177] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fda64ea5a55]
[runnervm0kj6c:08177] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fda64ea5a6f]
[runnervm0kj6c:08177] [ 8] plumed_master(+0x146dd)[0x563eae31e6dd]
[runnervm0kj6c:08177] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fda64a2a1ca]
[runnervm0kj6c:08177] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fda64a2a28b]
[runnervm0kj6c:08177] [11] plumed_master(+0x15365)[0x563eae31f365]
[runnervm0kj6c:08177] *** End of error message ***
</pre>
{% endraw %}
