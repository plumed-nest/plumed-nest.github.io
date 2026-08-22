**Project ID:** [plumID:20.026]({{ '/' | absolute_url }}eggs/20/026/)  
Stderr for source:  plumed_WTMD.dat   
Download: [zipped raw stdout](plumed_WTMD.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_WTMD.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s58 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervm76f27:09712] *** Process received signal ***
[runnervm76f27:09712] Signal: Aborted (6)
[runnervm76f27:09712] Signal code:  (-6)
[runnervm76f27:09712] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fdc84c45330]
[runnervm76f27:09712] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fdc84c9ec0c]
[runnervm76f27:09712] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fdc84c4527e]
[runnervm76f27:09712] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fdc84c288ff]
[runnervm76f27:09712] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fdc850a5ff5]
[runnervm76f27:09712] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fdc850bb0da]
[runnervm76f27:09712] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fdc850a5a55]
[runnervm76f27:09712] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fdc850a5a6f]
[runnervm76f27:09712] [ 8] plumed(+0x146dd)[0x5614e02556dd]
[runnervm76f27:09712] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fdc84c2a1ca]
[runnervm76f27:09712] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fdc84c2a28b]
[runnervm76f27:09712] [11] plumed(+0x15365)[0x5614e0256365]
[runnervm76f27:09712] *** End of error message ***
</pre>
{% endraw %}
