**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  h3/explicit/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @47 : keyword ARG is compulsory for this action
[fv-az797-511:10751] *** Process received signal ***
[fv-az797-511:10751] Signal: Aborted (6)
[fv-az797-511:10751] Signal code:  (-6)
[fv-az797-511:10751] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f079da45330]
[fv-az797-511:10751] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f079da9eb2c]
[fv-az797-511:10751] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f079da4527e]
[fv-az797-511:10751] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f079da288ff]
[fv-az797-511:10751] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f079dea5ff5]
[fv-az797-511:10751] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f079debb0da]
[fv-az797-511:10751] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f079dea5a55]
[fv-az797-511:10751] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f079dea5a6f]
[fv-az797-511:10751] [ 8] plumed_master(+0x146dd)[0x5583ecb0f6dd]
[fv-az797-511:10751] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f079da2a1ca]
[fv-az797-511:10751] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f079da2a28b]
[fv-az797-511:10751] [11] plumed_master(+0x15365)[0x5583ecb10365]
[fv-az797-511:10751] *** End of error message ***
</pre>
{% endraw %}
