**Project ID:** [plumID:23.016]({{ '/' | absolute_url }}eggs/23/016/)  
Stderr for source:  plumed_reweight_2D_microsw_adr_bin.dat   
Download: [zipped raw stdout](plumed_reweight_2D_microsw_adr_bin.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_reweight_2D_microsw_adr_bin.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s15 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervmgx7h7:07019] *** Process received signal ***
[runnervmgx7h7:07019] Signal: Aborted (6)
[runnervmgx7h7:07019] Signal code:  (-6)
[runnervmgx7h7:07019] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f639fa45330]
[runnervmgx7h7:07019] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f639fa9ec0c]
[runnervmgx7h7:07019] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f639fa4527e]
[runnervmgx7h7:07019] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f639fa288ff]
[runnervmgx7h7:07019] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f639fea5ff5]
[runnervmgx7h7:07019] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f639febb0da]
[runnervmgx7h7:07019] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f639fea5a55]
[runnervmgx7h7:07019] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f639fea5a6f]
[runnervmgx7h7:07019] [ 8] plumed(+0x146dd)[0x564f8f9666dd]
[runnervmgx7h7:07019] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f639fa2a1ca]
[runnervmgx7h7:07019] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f639fa2a28b]
[runnervmgx7h7:07019] [11] plumed(+0x15365)[0x564f8f967365]
[runnervmgx7h7:07019] *** End of error message ***
</pre>
{% endraw %}
