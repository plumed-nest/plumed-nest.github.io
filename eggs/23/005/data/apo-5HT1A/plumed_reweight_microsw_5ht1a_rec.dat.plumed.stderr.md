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
[runnervmvrwv9:06019] *** Process received signal ***
[runnervmvrwv9:06019] Signal: Aborted (6)
[runnervmvrwv9:06019] Signal code:  (-6)
[runnervmvrwv9:06019] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc87fa45330]
[runnervmvrwv9:06019] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc87fa9eb2c]
[runnervmvrwv9:06019] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc87fa4527e]
[runnervmvrwv9:06019] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc87fa288ff]
[runnervmvrwv9:06019] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc87fea5ff5]
[runnervmvrwv9:06019] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc87febb0da]
[runnervmvrwv9:06019] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc87fea5a55]
[runnervmvrwv9:06019] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc87fea5a6f]
[runnervmvrwv9:06019] [ 8] plumed(+0x146dd)[0x5585267196dd]
[runnervmvrwv9:06019] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc87fa2a1ca]
[runnervmvrwv9:06019] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc87fa2a28b]
[runnervmvrwv9:06019] [11] plumed(+0x15365)[0x55852671a365]
[runnervmvrwv9:06019] *** End of error message ***
</pre>
{% endraw %}
