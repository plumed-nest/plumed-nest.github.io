**Project ID:** [plumID:25.029]({{ '/' | absolute_url }}eggs/25/029/)  
Stderr for source:  ./crys/4-reweight_crys.dat   
Download: [zipped raw stdout](4-reweight_crys.dat.plumed.stdout.txt.zip) - [zipped raw stderr](4-reweight_crys.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s33 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervm76f27:04702] *** Process received signal ***
[runnervm76f27:04702] Signal: Aborted (6)
[runnervm76f27:04702] Signal code:  (-6)
[runnervm76f27:04702] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3119045330]
[runnervm76f27:04702] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f311909ec0c]
[runnervm76f27:04702] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f311904527e]
[runnervm76f27:04702] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f31190288ff]
[runnervm76f27:04702] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f31194a5ff5]
[runnervm76f27:04702] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f31194bb0da]
[runnervm76f27:04702] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f31194a5a55]
[runnervm76f27:04702] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f31194a5a6f]
[runnervm76f27:04702] [ 8] plumed(+0x146dd)[0x5576718ed6dd]
[runnervm76f27:04702] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f311902a1ca]
[runnervm76f27:04702] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f311902a28b]
[runnervm76f27:04702] [11] plumed(+0x15365)[0x5576718ee365]
[runnervm76f27:04702] *** End of error message ***
</pre>
{% endraw %}
