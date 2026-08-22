**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w19-s5.196/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervm76f27:09891] *** Process received signal ***
[runnervm76f27:09891] Signal: Aborted (6)
[runnervm76f27:09891] Signal code:  (-6)
[runnervm76f27:09891] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f29e5445330]
[runnervm76f27:09891] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f29e549ec0c]
[runnervm76f27:09891] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f29e544527e]
[runnervm76f27:09891] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f29e54288ff]
[runnervm76f27:09891] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f29e58a5ff5]
[runnervm76f27:09891] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f29e58bb0da]
[runnervm76f27:09891] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f29e58a5a55]
[runnervm76f27:09891] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f29e58a5a6f]
[runnervm76f27:09891] [ 8] plumed(+0x146dd)[0x563e42f226dd]
[runnervm76f27:09891] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f29e542a1ca]
[runnervm76f27:09891] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f29e542a28b]
[runnervm76f27:09891] [11] plumed(+0x15365)[0x563e42f23365]
[runnervm76f27:09891] *** End of error message ***
</pre>
{% endraw %}
