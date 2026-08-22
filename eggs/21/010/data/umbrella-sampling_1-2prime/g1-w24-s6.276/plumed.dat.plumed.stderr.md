**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w24-s6.276/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervm76f27:10199] *** Process received signal ***
[runnervm76f27:10199] Signal: Aborted (6)
[runnervm76f27:10199] Signal code:  (-6)
[runnervm76f27:10199] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fea45445330]
[runnervm76f27:10199] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fea4549ec0c]
[runnervm76f27:10199] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fea4544527e]
[runnervm76f27:10199] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fea454288ff]
[runnervm76f27:10199] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fea458a5ff5]
[runnervm76f27:10199] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fea458bb0da]
[runnervm76f27:10199] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fea458a5a55]
[runnervm76f27:10199] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fea458a5a6f]
[runnervm76f27:10199] [ 8] plumed(+0x146dd)[0x563d0bba86dd]
[runnervm76f27:10199] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fea4542a1ca]
[runnervm76f27:10199] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fea4542a28b]
[runnervm76f27:10199] [11] plumed(+0x15365)[0x563d0bba9365]
[runnervm76f27:10199] *** End of error message ***
</pre>
{% endraw %}
