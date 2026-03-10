**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test10_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervm0kj6c:06846] *** Process received signal ***
[runnervm0kj6c:06846] Signal: Aborted (6)
[runnervm0kj6c:06846] Signal code:  (-6)
[runnervm0kj6c:06846] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9029245330]
[runnervm0kj6c:06846] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f902929eb2c]
[runnervm0kj6c:06846] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f902924527e]
[runnervm0kj6c:06846] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f90292288ff]
[runnervm0kj6c:06846] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f90296a5ff5]
[runnervm0kj6c:06846] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f90296bb0da]
[runnervm0kj6c:06846] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f90296a5a55]
[runnervm0kj6c:06846] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f90296a5a6f]
[runnervm0kj6c:06846] [ 8] plumed(+0x146dd)[0x55724073d6dd]
[runnervm0kj6c:06846] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f902922a1ca]
[runnervm0kj6c:06846] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f902922a28b]
[runnervm0kj6c:06846] [11] plumed(+0x15365)[0x55724073e365]
[runnervm0kj6c:06846] *** End of error message ***
</pre>
{% endraw %}
