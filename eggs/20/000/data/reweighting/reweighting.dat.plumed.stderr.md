**Project ID:** [plumID:20.000]({{ '/' | absolute_url }}eggs/20/000/)  
Stderr for source:  reweighting/reweighting.dat   
Download: [zipped raw stdout](reweighting.dat.plumed.stdout.txt.zip) - [zipped raw stderr](reweighting.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s13 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervm76f27:10242] *** Process received signal ***
[runnervm76f27:10242] Signal: Aborted (6)
[runnervm76f27:10242] Signal code:  (-6)
[runnervm76f27:10242] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5056045330]
[runnervm76f27:10242] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f505609ec0c]
[runnervm76f27:10242] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f505604527e]
[runnervm76f27:10242] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f50560288ff]
[runnervm76f27:10242] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f50564a5ff5]
[runnervm76f27:10242] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f50564bb0da]
[runnervm76f27:10242] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f50564a5a55]
[runnervm76f27:10242] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f50564a5a6f]
[runnervm76f27:10242] [ 8] plumed(+0x146dd)[0x559a15e836dd]
[runnervm76f27:10242] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f505602a1ca]
[runnervm76f27:10242] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f505602a28b]
[runnervm76f27:10242] [11] plumed(+0x15365)[0x559a15e84365]
[runnervm76f27:10242] *** End of error message ***
</pre>
{% endraw %}
