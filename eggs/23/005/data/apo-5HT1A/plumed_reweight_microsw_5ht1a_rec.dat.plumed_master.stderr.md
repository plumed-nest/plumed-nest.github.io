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
[runnervmmklqx:06863] *** Process received signal ***
[runnervmmklqx:06863] Signal: Aborted (6)
[runnervmmklqx:06863] Signal code:  (-6)
[runnervmmklqx:06863] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7d0ac45330]
[runnervmmklqx:06863] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7d0ac9eb2c]
[runnervmmklqx:06863] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7d0ac4527e]
[runnervmmklqx:06863] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7d0ac288ff]
[runnervmmklqx:06863] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7d0b0a5ff5]
[runnervmmklqx:06863] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7d0b0bb0da]
[runnervmmklqx:06863] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7d0b0a5a55]
[runnervmmklqx:06863] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7d0b0a5a6f]
[runnervmmklqx:06863] [ 8] plumed_master(+0x146dd)[0x55f0119dd6dd]
[runnervmmklqx:06863] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7d0ac2a1ca]
[runnervmmklqx:06863] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7d0ac2a28b]
[runnervmmklqx:06863] [11] plumed_master(+0x15365)[0x55f0119de365]
[runnervmmklqx:06863] *** End of error message ***
</pre>
{% endraw %}
