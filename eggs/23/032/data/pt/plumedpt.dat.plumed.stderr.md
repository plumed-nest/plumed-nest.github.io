**Project ID:** [plumID:23.032]({{ '/' | absolute_url }}eggs/23/032/)  
Stderr for source:  pt/plumedpt.dat   
Download: [zipped raw stdout](plumedpt.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumedpt.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTORCH_MODEL_CV" is not known.
[runnervm0kj6c:08159] *** Process received signal ***
[runnervm0kj6c:08159] Signal: Aborted (6)
[runnervm0kj6c:08159] Signal code:  (-6)
[runnervm0kj6c:08159] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fea50e45330]
[runnervm0kj6c:08159] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fea50e9eb2c]
[runnervm0kj6c:08159] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fea50e4527e]
[runnervm0kj6c:08159] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fea50e288ff]
[runnervm0kj6c:08159] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fea512a5ff5]
[runnervm0kj6c:08159] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fea512bb0da]
[runnervm0kj6c:08159] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fea512a5a55]
[runnervm0kj6c:08159] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fea512a5a6f]
[runnervm0kj6c:08159] [ 8] plumed(+0x146dd)[0x557b5873e6dd]
[runnervm0kj6c:08159] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fea50e2a1ca]
[runnervm0kj6c:08159] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fea50e2a28b]
[runnervm0kj6c:08159] [11] plumed(+0x15365)[0x557b5873f365]
[runnervm0kj6c:08159] *** End of error message ***
</pre>
{% endraw %}
