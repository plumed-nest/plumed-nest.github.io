**Project ID:** [plumID:23.043]({{ '/' | absolute_url }}eggs/23/043/)  
Stderr for source:  metad-example/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "SPHERICAL_EXPANSION" is not known.
[runnervm0kj6c:05158] *** Process received signal ***
[runnervm0kj6c:05158] Signal: Aborted (6)
[runnervm0kj6c:05158] Signal code:  (-6)
[runnervm0kj6c:05158] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1d99a45330]
[runnervm0kj6c:05158] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1d99a9eb2c]
[runnervm0kj6c:05158] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1d99a4527e]
[runnervm0kj6c:05158] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1d99a288ff]
[runnervm0kj6c:05158] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1d99ea5ff5]
[runnervm0kj6c:05158] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1d99ebb0da]
[runnervm0kj6c:05158] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1d99ea5a55]
[runnervm0kj6c:05158] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1d99ea5a6f]
[runnervm0kj6c:05158] [ 8] plumed(+0x146dd)[0x56228626c6dd]
[runnervm0kj6c:05158] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1d99a2a1ca]
[runnervm0kj6c:05158] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1d99a2a28b]
[runnervm0kj6c:05158] [11] plumed(+0x15365)[0x56228626d365]
[runnervm0kj6c:05158] *** End of error message ***
</pre>
{% endraw %}
