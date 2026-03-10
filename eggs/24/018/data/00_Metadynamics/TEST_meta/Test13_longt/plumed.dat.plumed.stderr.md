**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test13_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervm0kj6c:07000] *** Process received signal ***
[runnervm0kj6c:07000] Signal: Aborted (6)
[runnervm0kj6c:07000] Signal code:  (-6)
[runnervm0kj6c:07000] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc285a45330]
[runnervm0kj6c:07000] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc285a9eb2c]
[runnervm0kj6c:07000] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc285a4527e]
[runnervm0kj6c:07000] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc285a288ff]
[runnervm0kj6c:07000] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc285ea5ff5]
[runnervm0kj6c:07000] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc285ebb0da]
[runnervm0kj6c:07000] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc285ea5a55]
[runnervm0kj6c:07000] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc285ea5a6f]
[runnervm0kj6c:07000] [ 8] plumed(+0x146dd)[0x55b2f13466dd]
[runnervm0kj6c:07000] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc285a2a1ca]
[runnervm0kj6c:07000] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc285a2a28b]
[runnervm0kj6c:07000] [11] plumed(+0x15365)[0x55b2f1347365]
[runnervm0kj6c:07000] *** End of error message ***
</pre>
{% endraw %}
