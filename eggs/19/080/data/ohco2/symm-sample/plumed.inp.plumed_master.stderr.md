**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  ohco2/symm-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @35 : keyword ARG is compulsory for this action
[fv-az2209-645:67810] *** Process received signal ***
[fv-az2209-645:67810] Signal: Aborted (6)
[fv-az2209-645:67810] Signal code:  (-6)
[fv-az2209-645:67810] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f79cbe45330]
[fv-az2209-645:67810] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f79cbe9eb2c]
[fv-az2209-645:67810] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f79cbe4527e]
[fv-az2209-645:67810] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f79cbe288ff]
[fv-az2209-645:67810] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f79cc2a5ff5]
[fv-az2209-645:67810] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f79cc2bb0da]
[fv-az2209-645:67810] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f79cc2a5a55]
[fv-az2209-645:67810] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f79cc2a5a6f]
[fv-az2209-645:67810] [ 8] plumed_master(+0x146dd)[0x5648299116dd]
[fv-az2209-645:67810] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f79cbe2a1ca]
[fv-az2209-645:67810] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f79cbe2a28b]
[fv-az2209-645:67810] [11] plumed_master(+0x15365)[0x564829912365]
[fv-az2209-645:67810] *** End of error message ***
</pre>
{% endraw %}
