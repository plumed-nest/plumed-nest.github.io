**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  clch3cl/ccl-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @33 : keyword ARG is compulsory for this action
[fv-az2209-645:68015] *** Process received signal ***
[fv-az2209-645:68015] Signal: Aborted (6)
[fv-az2209-645:68015] Signal code:  (-6)
[fv-az2209-645:68015] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0fc9045330]
[fv-az2209-645:68015] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0fc909eb2c]
[fv-az2209-645:68015] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0fc904527e]
[fv-az2209-645:68015] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0fc90288ff]
[fv-az2209-645:68015] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0fc94a5ff5]
[fv-az2209-645:68015] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0fc94bb0da]
[fv-az2209-645:68015] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0fc94a5a55]
[fv-az2209-645:68015] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0fc94a5a6f]
[fv-az2209-645:68015] [ 8] plumed_master(+0x146dd)[0x563337bdd6dd]
[fv-az2209-645:68015] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0fc902a1ca]
[fv-az2209-645:68015] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0fc902a28b]
[fv-az2209-645:68015] [11] plumed_master(+0x15365)[0x563337bde365]
[fv-az2209-645:68015] *** End of error message ***
</pre>
{% endraw %}
