**Project ID:** [plumID:23.016]({{ '/' | absolute_url }}eggs/23/016/)  
Stderr for source:  plumed_reweight_2D_microsw_adr_bin.dat   
Download: [zipped raw stdout](plumed_reweight_2D_microsw_adr_bin.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight_2D_microsw_adr_bin.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @90 : keyword ARG is compulsory for this action
[fv-az2035-366:07037] *** Process received signal ***
[fv-az2035-366:07037] Signal: Aborted (6)
[fv-az2035-366:07037] Signal code:  (-6)
[fv-az2035-366:07037] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fcacf045330]
[fv-az2035-366:07037] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fcacf09eb2c]
[fv-az2035-366:07037] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fcacf04527e]
[fv-az2035-366:07037] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fcacf0288ff]
[fv-az2035-366:07037] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fcacf4a5ff5]
[fv-az2035-366:07037] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fcacf4bb0da]
[fv-az2035-366:07037] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fcacf4a5a55]
[fv-az2035-366:07037] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fcacf4a5a6f]
[fv-az2035-366:07037] [ 8] plumed_master(+0x146dd)[0x556d6074a6dd]
[fv-az2035-366:07037] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fcacf02a1ca]
[fv-az2035-366:07037] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fcacf02a28b]
[fv-az2035-366:07037] [11] plumed_master(+0x15365)[0x556d6074b365]
[fv-az2035-366:07037] *** End of error message ***
</pre>
{% endraw %}
