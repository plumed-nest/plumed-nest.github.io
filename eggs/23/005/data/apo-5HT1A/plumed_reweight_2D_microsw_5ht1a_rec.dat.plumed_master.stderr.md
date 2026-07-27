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
[runnervmvrwv9:05983] *** Process received signal ***
[runnervmvrwv9:05983] Signal: Aborted (6)
[runnervmvrwv9:05983] Signal code:  (-6)
[runnervmvrwv9:05983] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0f4b645330]
[runnervmvrwv9:05983] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0f4b69eb2c]
[runnervmvrwv9:05983] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0f4b64527e]
[runnervmvrwv9:05983] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0f4b6288ff]
[runnervmvrwv9:05983] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0f4baa5ff5]
[runnervmvrwv9:05983] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0f4babb0da]
[runnervmvrwv9:05983] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0f4baa5a55]
[runnervmvrwv9:05983] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0f4baa5a6f]
[runnervmvrwv9:05983] [ 8] plumed_master(+0x146dd)[0x559617f006dd]
[runnervmvrwv9:05983] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0f4b62a1ca]
[runnervmvrwv9:05983] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0f4b62a28b]
[runnervmvrwv9:05983] [11] plumed_master(+0x15365)[0x559617f01365]
[runnervmvrwv9:05983] *** End of error message ***
</pre>
{% endraw %}
