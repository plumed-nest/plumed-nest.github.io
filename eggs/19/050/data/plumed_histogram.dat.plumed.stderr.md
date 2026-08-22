**Project ID:** [plumID:19.050]({{ '/' | absolute_url }}eggs/19/050/)  
Stderr for source:  plumed_histogram.dat   
Download: [zipped raw stdout](plumed_histogram.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_histogram.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s12 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervm76f27:10830] *** Process received signal ***
[runnervm76f27:10830] Signal: Aborted (6)
[runnervm76f27:10830] Signal code:  (-6)
[runnervm76f27:10830] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0760045330]
[runnervm76f27:10830] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f076009ec0c]
[runnervm76f27:10830] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f076004527e]
[runnervm76f27:10830] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f07600288ff]
[runnervm76f27:10830] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f07604a5ff5]
[runnervm76f27:10830] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f07604bb0da]
[runnervm76f27:10830] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f07604a5a55]
[runnervm76f27:10830] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f07604a5a6f]
[runnervm76f27:10830] [ 8] plumed(+0x146dd)[0x55d00917e6dd]
[runnervm76f27:10830] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f076002a1ca]
[runnervm76f27:10830] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f076002a28b]
[runnervm76f27:10830] [11] plumed(+0x15365)[0x55d00917f365]
[runnervm76f27:10830] *** End of error message ***
</pre>
{% endraw %}
