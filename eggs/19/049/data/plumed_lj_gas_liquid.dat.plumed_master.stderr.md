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
[fv-az1444-322:12469] *** Process received signal ***
[fv-az1444-322:12469] Signal: Aborted (6)
[fv-az1444-322:12469] Signal code:  (-6)
[fv-az1444-322:12469] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5acec45330]
[fv-az1444-322:12469] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5acec9eb2c]
[fv-az1444-322:12469] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5acec4527e]
[fv-az1444-322:12469] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5acec288ff]
[fv-az1444-322:12469] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5acf0a5ff5]
[fv-az1444-322:12469] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5acf0bb0da]
[fv-az1444-322:12469] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5acf0a5a55]
[fv-az1444-322:12469] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5acf0a5a6f]
[fv-az1444-322:12469] [ 8] plumed_master(+0x146dd)[0x55c93abef6dd]
[fv-az1444-322:12469] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5acec2a1ca]
[fv-az1444-322:12469] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5acec2a28b]
[fv-az1444-322:12469] [11] plumed_master(+0x15365)[0x55c93abf0365]
[fv-az1444-322:12469] *** End of error message ***
</pre>
{% endraw %}
