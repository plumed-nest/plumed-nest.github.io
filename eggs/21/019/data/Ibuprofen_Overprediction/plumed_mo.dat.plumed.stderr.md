**Project ID:** [plumID:21.019]({{ '/' | absolute_url }}eggs/21/019/)  
Stderr for source:  Ibuprofen_Overprediction/plumed_mo.dat   
Download: [zipped raw stdout](plumed_mo.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_mo.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATOMS285=9378,9382" is not known.
[runnervm0kj6c:09628] *** Process received signal ***
[runnervm0kj6c:09628] Signal: Aborted (6)
[runnervm0kj6c:09628] Signal code:  (-6)
[runnervm0kj6c:09628] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9ee5c45330]
[runnervm0kj6c:09628] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9ee5c9eb2c]
[runnervm0kj6c:09628] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9ee5c4527e]
[runnervm0kj6c:09628] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9ee5c288ff]
[runnervm0kj6c:09628] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9ee60a5ff5]
[runnervm0kj6c:09628] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9ee60bb0da]
[runnervm0kj6c:09628] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9ee60a5a55]
[runnervm0kj6c:09628] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9ee60a5a6f]
[runnervm0kj6c:09628] [ 8] plumed(+0x146dd)[0x563de0cc36dd]
[runnervm0kj6c:09628] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9ee5c2a1ca]
[runnervm0kj6c:09628] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9ee5c2a28b]
[runnervm0kj6c:09628] [11] plumed(+0x15365)[0x563de0cc4365]
[runnervm0kj6c:09628] *** End of error message ***
</pre>
{% endraw %}
