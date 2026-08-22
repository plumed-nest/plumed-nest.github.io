**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  hbr/metad/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s31 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervm76f27:08790] *** Process received signal ***
[runnervm76f27:08790] Signal: Aborted (6)
[runnervm76f27:08790] Signal code:  (-6)
[runnervm76f27:08790] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f612c245330]
[runnervm76f27:08790] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f612c29ec0c]
[runnervm76f27:08790] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f612c24527e]
[runnervm76f27:08790] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f612c2288ff]
[runnervm76f27:08790] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f612c6a5ff5]
[runnervm76f27:08790] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f612c6bb0da]
[runnervm76f27:08790] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f612c6a5a55]
[runnervm76f27:08790] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f612c6a5a6f]
[runnervm76f27:08790] [ 8] plumed_master(+0x146dd)[0x556a076396dd]
[runnervm76f27:08790] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f612c22a1ca]
[runnervm76f27:08790] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f612c22a28b]
[runnervm76f27:08790] [11] plumed_master(+0x15365)[0x556a0763a365]
[runnervm76f27:08790] *** End of error message ***
</pre>
{% endraw %}
