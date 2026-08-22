**Project ID:** [plumID:23.016]({{ '/' | absolute_url }}eggs/23/016/)  
Stderr for source:  plumed_reweight_2D_microsw_adr_bin.dat   
Download: [zipped raw stdout](plumed_reweight_2D_microsw_adr_bin.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_reweight_2D_microsw_adr_bin.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s15 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervm76f27:07691] *** Process received signal ***
[runnervm76f27:07691] Signal: Aborted (6)
[runnervm76f27:07691] Signal code:  (-6)
[runnervm76f27:07691] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd090e45330]
[runnervm76f27:07691] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd090e9ec0c]
[runnervm76f27:07691] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd090e4527e]
[runnervm76f27:07691] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd090e288ff]
[runnervm76f27:07691] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd0912a5ff5]
[runnervm76f27:07691] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd0912bb0da]
[runnervm76f27:07691] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd0912a5a55]
[runnervm76f27:07691] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd0912a5a6f]
[runnervm76f27:07691] [ 8] plumed(+0x146dd)[0x55e257e4d6dd]
[runnervm76f27:07691] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd090e2a1ca]
[runnervm76f27:07691] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd090e2a28b]
[runnervm76f27:07691] [11] plumed(+0x15365)[0x55e257e4e365]
[runnervm76f27:07691] *** End of error message ***
</pre>
{% endraw %}
