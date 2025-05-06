**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  sn2/fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @44 : keyword ARG is compulsory for this action
[fv-az2209-645:64771] *** Process received signal ***
[fv-az2209-645:64771] Signal: Aborted (6)
[fv-az2209-645:64771] Signal code:  (-6)
[fv-az2209-645:64771] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6d07645330]
[fv-az2209-645:64771] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6d0769eb2c]
[fv-az2209-645:64771] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6d0764527e]
[fv-az2209-645:64771] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6d076288ff]
[fv-az2209-645:64771] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6d07aa5ff5]
[fv-az2209-645:64771] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6d07abb0da]
[fv-az2209-645:64771] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6d07aa5a55]
[fv-az2209-645:64771] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6d07aa5a6f]
[fv-az2209-645:64771] [ 8] plumed_master(+0x146dd)[0x56271c19f6dd]
[fv-az2209-645:64771] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6d0762a1ca]
[fv-az2209-645:64771] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6d0762a28b]
[fv-az2209-645:64771] [11] plumed_master(+0x15365)[0x56271c1a0365]
[fv-az2209-645:64771] *** End of error message ***
</pre>
{% endraw %}
