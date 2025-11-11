**Project ID:** [plumID:23.005]({{ '/' | absolute_url }}eggs/23/005/)  
Stderr for source:  apo-5HT1A/plumed_reweight_microsw_5ht1a_rec.dat   
Download: [zipped raw stdout](plumed_reweight_microsw_5ht1a_rec.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight_microsw_5ht1a_rec.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @73 : keyword ARG is compulsory for this action
[runnervmw9dnm:08480] *** Process received signal ***
[runnervmw9dnm:08480] Signal: Aborted (6)
[runnervmw9dnm:08480] Signal code:  (-6)
[runnervmw9dnm:08480] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f39bd845330]
[runnervmw9dnm:08480] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f39bd89eb2c]
[runnervmw9dnm:08480] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f39bd84527e]
[runnervmw9dnm:08480] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f39bd8288ff]
[runnervmw9dnm:08480] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f39bdca5ff5]
[runnervmw9dnm:08480] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f39bdcbb0da]
[runnervmw9dnm:08480] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f39bdca5a55]
[runnervmw9dnm:08480] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f39bdca5a6f]
[runnervmw9dnm:08480] [ 8] plumed_master(+0x146dd)[0x55650f2776dd]
[runnervmw9dnm:08480] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f39bd82a1ca]
[runnervmw9dnm:08480] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f39bd82a28b]
[runnervmw9dnm:08480] [11] plumed_master(+0x15365)[0x55650f278365]
[runnervmw9dnm:08480] *** End of error message ***
</pre>
{% endraw %}
