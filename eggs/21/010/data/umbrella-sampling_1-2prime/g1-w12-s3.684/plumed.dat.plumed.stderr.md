**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w12-s3.684/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervm76f27:09528] *** Process received signal ***
[runnervm76f27:09528] Signal: Aborted (6)
[runnervm76f27:09528] Signal code:  (-6)
[runnervm76f27:09528] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f48f2645330]
[runnervm76f27:09528] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f48f269ec0c]
[runnervm76f27:09528] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f48f264527e]
[runnervm76f27:09528] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f48f26288ff]
[runnervm76f27:09528] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f48f2aa5ff5]
[runnervm76f27:09528] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f48f2abb0da]
[runnervm76f27:09528] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f48f2aa5a55]
[runnervm76f27:09528] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f48f2aa5a6f]
[runnervm76f27:09528] [ 8] plumed(+0x146dd)[0x5643095f76dd]
[runnervm76f27:09528] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f48f262a1ca]
[runnervm76f27:09528] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f48f262a28b]
[runnervm76f27:09528] [11] plumed(+0x15365)[0x5643095f8365]
[runnervm76f27:09528] *** End of error message ***
</pre>
{% endraw %}
