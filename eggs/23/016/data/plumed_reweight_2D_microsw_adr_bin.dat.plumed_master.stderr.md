**Project ID:** [plumID:23.016]({{ '/' | absolute_url }}eggs/23/016/)  
Stderr for source:  plumed_reweight_2D_microsw_adr_bin.dat   
Download: [zipped raw stdout](plumed_reweight_2D_microsw_adr_bin.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight_2D_microsw_adr_bin.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @60 : keyword ARG is compulsory for this action
[runnervmw9dnm:07688] *** Process received signal ***
[runnervmw9dnm:07688] Signal: Aborted (6)
[runnervmw9dnm:07688] Signal code:  (-6)
[runnervmw9dnm:07688] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa046045330]
[runnervmw9dnm:07688] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa04609eb2c]
[runnervmw9dnm:07688] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa04604527e]
[runnervmw9dnm:07688] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa0460288ff]
[runnervmw9dnm:07688] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa0464a5ff5]
[runnervmw9dnm:07688] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa0464bb0da]
[runnervmw9dnm:07688] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa0464a5a55]
[runnervmw9dnm:07688] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa0464a5a6f]
[runnervmw9dnm:07688] [ 8] plumed_master(+0x146dd)[0x564af43a66dd]
[runnervmw9dnm:07688] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa04602a1ca]
[runnervmw9dnm:07688] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa04602a28b]
[runnervmw9dnm:07688] [11] plumed_master(+0x15365)[0x564af43a7365]
[runnervmw9dnm:07688] *** End of error message ***
</pre>
{% endraw %}
