**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  h3/sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @33 : keyword ARG is compulsory for this action
[fv-az797-511:10842] *** Process received signal ***
[fv-az797-511:10842] Signal: Aborted (6)
[fv-az797-511:10842] Signal code:  (-6)
[fv-az797-511:10842] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbd21a45330]
[fv-az797-511:10842] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbd21a9eb2c]
[fv-az797-511:10842] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbd21a4527e]
[fv-az797-511:10842] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbd21a288ff]
[fv-az797-511:10842] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbd21ea5ff5]
[fv-az797-511:10842] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbd21ebb0da]
[fv-az797-511:10842] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbd21ea5a55]
[fv-az797-511:10842] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbd21ea5a6f]
[fv-az797-511:10842] [ 8] plumed_master(+0x146dd)[0x5644e7cc06dd]
[fv-az797-511:10842] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbd21a2a1ca]
[fv-az797-511:10842] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbd21a2a28b]
[fv-az797-511:10842] [11] plumed_master(+0x15365)[0x5644e7cc1365]
[fv-az797-511:10842] *** End of error message ***
</pre>
{% endraw %}
