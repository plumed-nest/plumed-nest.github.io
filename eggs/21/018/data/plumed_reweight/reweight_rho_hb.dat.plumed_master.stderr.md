**Project ID:** [plumID:21.018]({{ '/' | absolute_url }}eggs/21/018/)  
Stderr for source:  plumed_reweight/reweight_rho_hb.dat   
Download: [zipped raw stdout](reweight_rho_hb.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](reweight_rho_hb.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
WARNING: IFile closed in the middle of reading. seems strange!
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s13 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervm76f27:09488] *** Process received signal ***
[runnervm76f27:09488] Signal: Aborted (6)
[runnervm76f27:09488] Signal code:  (-6)
[runnervm76f27:09488] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc327c45330]
[runnervm76f27:09488] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc327c9ec0c]
[runnervm76f27:09488] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc327c4527e]
[runnervm76f27:09488] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc327c288ff]
[runnervm76f27:09488] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc3280a5ff5]
[runnervm76f27:09488] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc3280bb0da]
[runnervm76f27:09488] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc3280a5a55]
[runnervm76f27:09488] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc3280a5a6f]
[runnervm76f27:09488] [ 8] plumed_master(+0x146dd)[0x561baef296dd]
[runnervm76f27:09488] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc327c2a1ca]
[runnervm76f27:09488] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc327c2a28b]
[runnervm76f27:09488] [11] plumed_master(+0x15365)[0x561baef2a365]
[runnervm76f27:09488] *** End of error message ***
</pre>
{% endraw %}
