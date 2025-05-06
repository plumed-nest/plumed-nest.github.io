**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_lj_gas_liquid.dat   
Download: [zipped raw stdout](plumed_lj_gas_liquid.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_lj_gas_liquid.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DFSCLUSTERING with label dfs : keyword ARG is compulsory for this action
[fv-az1781-652:67981] *** Process received signal ***
[fv-az1781-652:67981] Signal: Aborted (6)
[fv-az1781-652:67981] Signal code:  (-6)
[fv-az1781-652:67981] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbd21245330]
[fv-az1781-652:67981] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbd2129eb2c]
[fv-az1781-652:67981] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbd2124527e]
[fv-az1781-652:67981] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbd212288ff]
[fv-az1781-652:67981] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbd216a5ff5]
[fv-az1781-652:67981] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbd216bb0da]
[fv-az1781-652:67981] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbd216a5a55]
[fv-az1781-652:67981] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbd216a5a6f]
[fv-az1781-652:67981] [ 8] plumed_master(+0x146dd)[0x55df192f26dd]
[fv-az1781-652:67981] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbd2122a1ca]
[fv-az1781-652:67981] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbd2122a28b]
[fv-az1781-652:67981] [11] plumed_master(+0x15365)[0x55df192f3365]
[fv-az1781-652:67981] *** End of error message ***
</pre>
{% endraw %}
