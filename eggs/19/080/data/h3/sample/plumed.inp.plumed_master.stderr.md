**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  h3/sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @33 : keyword ARG is compulsory for this action
[fv-az1979-234:67378] *** Process received signal ***
[fv-az1979-234:67378] Signal: Aborted (6)
[fv-az1979-234:67378] Signal code:  (-6)
[fv-az1979-234:67378] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9679045330]
[fv-az1979-234:67378] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f967909eb2c]
[fv-az1979-234:67378] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f967904527e]
[fv-az1979-234:67378] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f96790288ff]
[fv-az1979-234:67378] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f96794a5ff5]
[fv-az1979-234:67378] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f96794bb0da]
[fv-az1979-234:67378] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f96794a5a55]
[fv-az1979-234:67378] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f96794a5a6f]
[fv-az1979-234:67378] [ 8] plumed_master(+0x146dd)[0x55ac9c39c6dd]
[fv-az1979-234:67378] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f967902a1ca]
[fv-az1979-234:67378] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f967902a28b]
[fv-az1979-234:67378] [11] plumed_master(+0x15365)[0x55ac9c39d365]
[fv-az1979-234:67378] *** End of error message ***
</pre>
{% endraw %}
