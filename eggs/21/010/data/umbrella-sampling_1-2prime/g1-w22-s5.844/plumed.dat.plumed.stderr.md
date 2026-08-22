**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w22-s5.844/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervm76f27:10096] *** Process received signal ***
[runnervm76f27:10096] Signal: Aborted (6)
[runnervm76f27:10096] Signal code:  (-6)
[runnervm76f27:10096] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f16c2245330]
[runnervm76f27:10096] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f16c229ec0c]
[runnervm76f27:10096] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f16c224527e]
[runnervm76f27:10096] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f16c22288ff]
[runnervm76f27:10096] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f16c26a5ff5]
[runnervm76f27:10096] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f16c26bb0da]
[runnervm76f27:10096] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f16c26a5a55]
[runnervm76f27:10096] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f16c26a5a6f]
[runnervm76f27:10096] [ 8] plumed(+0x146dd)[0x55d54ee086dd]
[runnervm76f27:10096] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f16c222a1ca]
[runnervm76f27:10096] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f16c222a28b]
[runnervm76f27:10096] [11] plumed(+0x15365)[0x55d54ee09365]
[runnervm76f27:10096] *** End of error message ***
</pre>
{% endraw %}
