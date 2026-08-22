**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w27-s6.924/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervm76f27:10355] *** Process received signal ***
[runnervm76f27:10355] Signal: Aborted (6)
[runnervm76f27:10355] Signal code:  (-6)
[runnervm76f27:10355] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9803e45330]
[runnervm76f27:10355] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9803e9ec0c]
[runnervm76f27:10355] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9803e4527e]
[runnervm76f27:10355] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9803e288ff]
[runnervm76f27:10355] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f98042a5ff5]
[runnervm76f27:10355] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f98042bb0da]
[runnervm76f27:10355] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f98042a5a55]
[runnervm76f27:10355] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f98042a5a6f]
[runnervm76f27:10355] [ 8] plumed(+0x146dd)[0x56199479b6dd]
[runnervm76f27:10355] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9803e2a1ca]
[runnervm76f27:10355] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9803e2a28b]
[runnervm76f27:10355] [11] plumed(+0x15365)[0x56199479c365]
[runnervm76f27:10355] *** End of error message ***
</pre>
{% endraw %}
