**Project ID:** [plumID:23.005]({{ '/' | absolute_url }}eggs/23/005/)  
Stderr for source:  apo-5HT1A/plumed_reweight_2D_microsw_5ht1a_rec.dat   
Download: [zipped raw stdout](plumed_reweight_2D_microsw_5ht1a_rec.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_reweight_2D_microsw_5ht1a_rec.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s15 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervmvrwv9:05967] *** Process received signal ***
[runnervmvrwv9:05967] Signal: Aborted (6)
[runnervmvrwv9:05967] Signal code:  (-6)
[runnervmvrwv9:05967] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7631045330]
[runnervmvrwv9:05967] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f763109eb2c]
[runnervmvrwv9:05967] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f763104527e]
[runnervmvrwv9:05967] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f76310288ff]
[runnervmvrwv9:05967] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f76314a5ff5]
[runnervmvrwv9:05967] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f76314bb0da]
[runnervmvrwv9:05967] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f76314a5a55]
[runnervmvrwv9:05967] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f76314a5a6f]
[runnervmvrwv9:05967] [ 8] plumed(+0x146dd)[0x560f44b606dd]
[runnervmvrwv9:05967] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f763102a1ca]
[runnervmvrwv9:05967] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f763102a28b]
[runnervmvrwv9:05967] [11] plumed(+0x15365)[0x560f44b61365]
[runnervmvrwv9:05967] *** End of error message ***
</pre>
{% endraw %}
