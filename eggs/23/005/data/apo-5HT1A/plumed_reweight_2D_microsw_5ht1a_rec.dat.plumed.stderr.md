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
[runnervmmklqx:06794] *** Process received signal ***
[runnervmmklqx:06794] Signal: Aborted (6)
[runnervmmklqx:06794] Signal code:  (-6)
[runnervmmklqx:06794] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2b51845330]
[runnervmmklqx:06794] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2b5189eb2c]
[runnervmmklqx:06794] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2b5184527e]
[runnervmmklqx:06794] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2b518288ff]
[runnervmmklqx:06794] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2b51ca5ff5]
[runnervmmklqx:06794] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2b51cbb0da]
[runnervmmklqx:06794] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2b51ca5a55]
[runnervmmklqx:06794] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2b51ca5a6f]
[runnervmmklqx:06794] [ 8] plumed(+0x146dd)[0x563e86e896dd]
[runnervmmklqx:06794] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2b5182a1ca]
[runnervmmklqx:06794] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2b5182a28b]
[runnervmmklqx:06794] [11] plumed(+0x15365)[0x563e86e8a365]
[runnervmmklqx:06794] *** End of error message ***
</pre>
{% endraw %}
