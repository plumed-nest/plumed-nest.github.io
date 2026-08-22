**Project ID:** [plumID:23.005]({{ '/' | absolute_url }}eggs/23/005/)  
Stderr for source:  apo-5HT1A/plumed_reweight_microsw_5ht1a_rec.dat   
Download: [zipped raw stdout](plumed_reweight_microsw_5ht1a_rec.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight_microsw_5ht1a_rec.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s15 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervm76f27:06055] *** Process received signal ***
[runnervm76f27:06055] Signal: Aborted (6)
[runnervm76f27:06055] Signal code:  (-6)
[runnervm76f27:06055] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f647ee45330]
[runnervm76f27:06055] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f647ee9ec0c]
[runnervm76f27:06055] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f647ee4527e]
[runnervm76f27:06055] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f647ee288ff]
[runnervm76f27:06055] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f647f2a5ff5]
[runnervm76f27:06055] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f647f2bb0da]
[runnervm76f27:06055] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f647f2a5a55]
[runnervm76f27:06055] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f647f2a5a6f]
[runnervm76f27:06055] [ 8] plumed_master(+0x146dd)[0x5611a56a96dd]
[runnervm76f27:06055] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f647ee2a1ca]
[runnervm76f27:06055] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f647ee2a28b]
[runnervm76f27:06055] [11] plumed_master(+0x15365)[0x5611a56aa365]
[runnervm76f27:06055] *** End of error message ***
</pre>
{% endraw %}
