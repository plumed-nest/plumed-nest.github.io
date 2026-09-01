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
[runnervmgx7h7:07052] *** Process received signal ***
[runnervmgx7h7:07052] Signal: Aborted (6)
[runnervmgx7h7:07052] Signal code:  (-6)
[runnervmgx7h7:07052] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f15c9845330]
[runnervmgx7h7:07052] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f15c989ec0c]
[runnervmgx7h7:07052] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f15c984527e]
[runnervmgx7h7:07052] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f15c98288ff]
[runnervmgx7h7:07052] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f15c9ca5ff5]
[runnervmgx7h7:07052] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f15c9cbb0da]
[runnervmgx7h7:07052] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f15c9ca5a55]
[runnervmgx7h7:07052] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f15c9ca5a6f]
[runnervmgx7h7:07052] [ 8] plumed(+0x146dd)[0x55a57ea286dd]
[runnervmgx7h7:07052] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f15c982a1ca]
[runnervmgx7h7:07052] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f15c982a28b]
[runnervmgx7h7:07052] [11] plumed(+0x15365)[0x55a57ea29365]
[runnervmgx7h7:07052] *** End of error message ***
</pre>
{% endraw %}
