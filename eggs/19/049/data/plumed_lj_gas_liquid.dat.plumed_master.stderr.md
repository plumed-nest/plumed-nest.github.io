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
[fv-az1921-959:69642] *** Process received signal ***
[fv-az1921-959:69642] Signal: Aborted (6)
[fv-az1921-959:69642] Signal code:  (-6)
[fv-az1921-959:69642] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f21d6045330]
[fv-az1921-959:69642] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f21d609eb2c]
[fv-az1921-959:69642] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f21d604527e]
[fv-az1921-959:69642] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f21d60288ff]
[fv-az1921-959:69642] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f21d64a5ff5]
[fv-az1921-959:69642] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f21d64bb0da]
[fv-az1921-959:69642] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f21d64a5a55]
[fv-az1921-959:69642] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f21d64a5a6f]
[fv-az1921-959:69642] [ 8] plumed_master(+0x146dd)[0x55710d5c36dd]
[fv-az1921-959:69642] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f21d602a1ca]
[fv-az1921-959:69642] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f21d602a28b]
[fv-az1921-959:69642] [11] plumed_master(+0x15365)[0x55710d5c4365]
[fv-az1921-959:69642] *** End of error message ***
</pre>
{% endraw %}
