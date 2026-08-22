**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w25-s6.492/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervm76f27:10252] *** Process received signal ***
[runnervm76f27:10252] Signal: Aborted (6)
[runnervm76f27:10252] Signal code:  (-6)
[runnervm76f27:10252] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0936c45330]
[runnervm76f27:10252] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0936c9ec0c]
[runnervm76f27:10252] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0936c4527e]
[runnervm76f27:10252] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0936c288ff]
[runnervm76f27:10252] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f09370a5ff5]
[runnervm76f27:10252] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f09370bb0da]
[runnervm76f27:10252] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f09370a5a55]
[runnervm76f27:10252] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f09370a5a6f]
[runnervm76f27:10252] [ 8] plumed(+0x146dd)[0x55aceb7296dd]
[runnervm76f27:10252] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0936c2a1ca]
[runnervm76f27:10252] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0936c2a28b]
[runnervm76f27:10252] [11] plumed(+0x15365)[0x55aceb72a365]
[runnervm76f27:10252] *** End of error message ***
</pre>
{% endraw %}
