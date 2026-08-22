**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test13_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervm76f27:05910] *** Process received signal ***
[runnervm76f27:05910] Signal: Aborted (6)
[runnervm76f27:05910] Signal code:  (-6)
[runnervm76f27:05910] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc8c9845330]
[runnervm76f27:05910] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc8c989ec0c]
[runnervm76f27:05910] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc8c984527e]
[runnervm76f27:05910] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc8c98288ff]
[runnervm76f27:05910] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc8c9ca5ff5]
[runnervm76f27:05910] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc8c9cbb0da]
[runnervm76f27:05910] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc8c9ca5a55]
[runnervm76f27:05910] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc8c9ca5a6f]
[runnervm76f27:05910] [ 8] plumed(+0x146dd)[0x56112358a6dd]
[runnervm76f27:05910] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc8c982a1ca]
[runnervm76f27:05910] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc8c982a28b]
[runnervm76f27:05910] [11] plumed(+0x15365)[0x56112358b365]
[runnervm76f27:05910] *** End of error message ***
</pre>
{% endraw %}
