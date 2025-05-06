**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-base/bend-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @60 : keyword ARG is compulsory for this action
[fv-az1110-827:63636] *** Process received signal ***
[fv-az1110-827:63636] Signal: Aborted (6)
[fv-az1110-827:63636] Signal code:  (-6)
[fv-az1110-827:63636] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa0f7e45330]
[fv-az1110-827:63636] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa0f7e9eb2c]
[fv-az1110-827:63636] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa0f7e4527e]
[fv-az1110-827:63636] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa0f7e288ff]
[fv-az1110-827:63636] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa0f82a5ff5]
[fv-az1110-827:63636] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa0f82bb0da]
[fv-az1110-827:63636] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa0f82a5a55]
[fv-az1110-827:63636] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa0f82a5a6f]
[fv-az1110-827:63636] [ 8] plumed_master(+0x146dd)[0x55b30b5566dd]
[fv-az1110-827:63636] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa0f7e2a1ca]
[fv-az1110-827:63636] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa0f7e2a28b]
[fv-az1110-827:63636] [11] plumed_master(+0x15365)[0x55b30b557365]
[fv-az1110-827:63636] *** End of error message ***
</pre>
{% endraw %}
