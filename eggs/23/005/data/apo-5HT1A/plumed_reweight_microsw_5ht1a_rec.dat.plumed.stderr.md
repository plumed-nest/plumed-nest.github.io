**Project ID:** [plumID:23.005]({{ '/' | absolute_url }}eggs/23/005/)  
Stderr for source:  apo-5HT1A/plumed_reweight_microsw_5ht1a_rec.dat   
Download: [zipped raw stdout](plumed_reweight_microsw_5ht1a_rec.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_reweight_microsw_5ht1a_rec.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s15 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervm76f27:06039] *** Process received signal ***
[runnervm76f27:06039] Signal: Aborted (6)
[runnervm76f27:06039] Signal code:  (-6)
[runnervm76f27:06039] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f55fac45330]
[runnervm76f27:06039] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f55fac9ec0c]
[runnervm76f27:06039] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f55fac4527e]
[runnervm76f27:06039] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f55fac288ff]
[runnervm76f27:06039] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f55fb0a5ff5]
[runnervm76f27:06039] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f55fb0bb0da]
[runnervm76f27:06039] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f55fb0a5a55]
[runnervm76f27:06039] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f55fb0a5a6f]
[runnervm76f27:06039] [ 8] plumed(+0x146dd)[0x5572f148f6dd]
[runnervm76f27:06039] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f55fac2a1ca]
[runnervm76f27:06039] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f55fac2a28b]
[runnervm76f27:06039] [11] plumed(+0x15365)[0x5572f1490365]
[runnervm76f27:06039] *** End of error message ***
</pre>
{% endraw %}
