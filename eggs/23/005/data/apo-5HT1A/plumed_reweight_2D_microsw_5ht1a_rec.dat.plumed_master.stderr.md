**Project ID:** [plumID:23.005]({{ '/' | absolute_url }}eggs/23/005/)  
Stderr for source:  apo-5HT1A/plumed_reweight_2D_microsw_5ht1a_rec.dat   
Download: [zipped raw stdout](plumed_reweight_2D_microsw_5ht1a_rec.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight_2D_microsw_5ht1a_rec.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s15 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervmgx7h7:07067] *** Process received signal ***
[runnervmgx7h7:07067] Signal: Aborted (6)
[runnervmgx7h7:07067] Signal code:  (-6)
[runnervmgx7h7:07067] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5f7c645330]
[runnervmgx7h7:07067] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5f7c69ec0c]
[runnervmgx7h7:07067] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5f7c64527e]
[runnervmgx7h7:07067] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5f7c6288ff]
[runnervmgx7h7:07067] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5f7caa5ff5]
[runnervmgx7h7:07067] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5f7cabb0da]
[runnervmgx7h7:07067] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5f7caa5a55]
[runnervmgx7h7:07067] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5f7caa5a6f]
[runnervmgx7h7:07067] [ 8] plumed_master(+0x146dd)[0x5570b52ca6dd]
[runnervmgx7h7:07067] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5f7c62a1ca]
[runnervmgx7h7:07067] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5f7c62a28b]
[runnervmgx7h7:07067] [11] plumed_master(+0x15365)[0x5570b52cb365]
[runnervmgx7h7:07067] *** End of error message ***
</pre>
{% endraw %}
