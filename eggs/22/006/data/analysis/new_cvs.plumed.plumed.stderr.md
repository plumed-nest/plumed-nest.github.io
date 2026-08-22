**Project ID:** [plumID:22.006]({{ '/' | absolute_url }}eggs/22/006/)  
Stderr for source:  analysis/new_cvs.plumed   
Download: [zipped raw stdout](new_cvs.plumed.plumed.stdout.txt.zip) - [zipped raw stderr](new_cvs.plumed.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s46 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervm76f27:07932] *** Process received signal ***
[runnervm76f27:07932] Signal: Aborted (6)
[runnervm76f27:07932] Signal code:  (-6)
[runnervm76f27:07932] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f97ee845330]
[runnervm76f27:07932] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f97ee89ec0c]
[runnervm76f27:07932] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f97ee84527e]
[runnervm76f27:07932] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f97ee8288ff]
[runnervm76f27:07932] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f97eeca5ff5]
[runnervm76f27:07932] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f97eecbb0da]
[runnervm76f27:07932] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f97eeca5a55]
[runnervm76f27:07932] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f97eeca5a6f]
[runnervm76f27:07932] [ 8] plumed(+0x146dd)[0x5568719166dd]
[runnervm76f27:07932] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f97ee82a1ca]
[runnervm76f27:07932] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f97ee82a28b]
[runnervm76f27:07932] [11] plumed(+0x15365)[0x556871917365]
[runnervm76f27:07932] *** End of error message ***
</pre>
{% endraw %}
