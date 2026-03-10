**Project ID:** [plumID:24.009]({{ '/' | absolute_url }}eggs/24/009/)  
Stderr for source:  actin_lda_setup/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "LDA_PROJ" is not known.
[runnervm0kj6c:07836] *** Process received signal ***
[runnervm0kj6c:07836] Signal: Aborted (6)
[runnervm0kj6c:07836] Signal code:  (-6)
[runnervm0kj6c:07836] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fceaea45330]
[runnervm0kj6c:07836] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fceaea9eb2c]
[runnervm0kj6c:07836] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fceaea4527e]
[runnervm0kj6c:07836] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fceaea288ff]
[runnervm0kj6c:07836] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fceaeea5ff5]
[runnervm0kj6c:07836] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fceaeebb0da]
[runnervm0kj6c:07836] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fceaeea5a55]
[runnervm0kj6c:07836] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fceaeea5a6f]
[runnervm0kj6c:07836] [ 8] plumed(+0x146dd)[0x5626119e16dd]
[runnervm0kj6c:07836] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fceaea2a1ca]
[runnervm0kj6c:07836] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fceaea2a28b]
[runnervm0kj6c:07836] [11] plumed(+0x15365)[0x5626119e2365]
[runnervm0kj6c:07836] *** End of error message ***
</pre>
{% endraw %}
