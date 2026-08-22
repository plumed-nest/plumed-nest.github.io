**Project ID:** [plumID:20.005]({{ '/' | absolute_url }}eggs/20/005/)  
Stderr for source:  input_data/classical/reweighting/reweighting.dat   
Download: [zipped raw stdout](reweighting.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](reweighting.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s12 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervm76f27:09915] *** Process received signal ***
[runnervm76f27:09915] Signal: Aborted (6)
[runnervm76f27:09915] Signal code:  (-6)
[runnervm76f27:09915] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f97f4e45330]
[runnervm76f27:09915] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f97f4e9ec0c]
[runnervm76f27:09915] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f97f4e4527e]
[runnervm76f27:09915] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f97f4e288ff]
[runnervm76f27:09915] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f97f52a5ff5]
[runnervm76f27:09915] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f97f52bb0da]
[runnervm76f27:09915] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f97f52a5a55]
[runnervm76f27:09915] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f97f52a5a6f]
[runnervm76f27:09915] [ 8] plumed_master(+0x146dd)[0x55c260b3c6dd]
[runnervm76f27:09915] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f97f4e2a1ca]
[runnervm76f27:09915] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f97f4e2a28b]
[runnervm76f27:09915] [11] plumed_master(+0x15365)[0x55c260b3d365]
[runnervm76f27:09915] *** End of error message ***
</pre>
{% endraw %}
