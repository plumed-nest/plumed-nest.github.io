**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  dimer/fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s19 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervm76f27:08520] *** Process received signal ***
[runnervm76f27:08520] Signal: Aborted (6)
[runnervm76f27:08520] Signal code:  (-6)
[runnervm76f27:08520] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f532f845330]
[runnervm76f27:08520] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f532f89ec0c]
[runnervm76f27:08520] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f532f84527e]
[runnervm76f27:08520] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f532f8288ff]
[runnervm76f27:08520] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f532fca5ff5]
[runnervm76f27:08520] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f532fcbb0da]
[runnervm76f27:08520] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f532fca5a55]
[runnervm76f27:08520] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f532fca5a6f]
[runnervm76f27:08520] [ 8] plumed(+0x146dd)[0x55e1b28836dd]
[runnervm76f27:08520] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f532f82a1ca]
[runnervm76f27:08520] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f532f82a28b]
[runnervm76f27:08520] [11] plumed(+0x15365)[0x55e1b2884365]
[runnervm76f27:08520] *** End of error message ***
</pre>
{% endraw %}
