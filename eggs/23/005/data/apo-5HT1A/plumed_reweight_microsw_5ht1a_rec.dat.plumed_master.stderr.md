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
[runnervmvrwv9:06035] *** Process received signal ***
[runnervmvrwv9:06035] Signal: Aborted (6)
[runnervmvrwv9:06035] Signal code:  (-6)
[runnervmvrwv9:06035] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa300c45330]
[runnervmvrwv9:06035] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa300c9eb2c]
[runnervmvrwv9:06035] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa300c4527e]
[runnervmvrwv9:06035] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa300c288ff]
[runnervmvrwv9:06035] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa3010a5ff5]
[runnervmvrwv9:06035] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa3010bb0da]
[runnervmvrwv9:06035] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa3010a5a55]
[runnervmvrwv9:06035] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa3010a5a6f]
[runnervmvrwv9:06035] [ 8] plumed_master(+0x146dd)[0x5588a1e4d6dd]
[runnervmvrwv9:06035] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa300c2a1ca]
[runnervmvrwv9:06035] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa300c2a28b]
[runnervmvrwv9:06035] [11] plumed_master(+0x15365)[0x5588a1e4e365]
[runnervmvrwv9:06035] *** End of error message ***
</pre>
{% endraw %}
