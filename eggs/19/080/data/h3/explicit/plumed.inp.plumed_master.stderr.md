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
[fv-az1695-570:12329] *** Process received signal ***
[fv-az1695-570:12329] Signal: Aborted (6)
[fv-az1695-570:12329] Signal code:  (-6)
[fv-az1695-570:12329] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f55c7445330]
[fv-az1695-570:12329] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f55c749eb2c]
[fv-az1695-570:12329] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f55c744527e]
[fv-az1695-570:12329] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f55c74288ff]
[fv-az1695-570:12329] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f55c78a5ff5]
[fv-az1695-570:12329] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f55c78bb0da]
[fv-az1695-570:12329] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f55c78a5a55]
[fv-az1695-570:12329] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f55c78a5a6f]
[fv-az1695-570:12329] [ 8] plumed_master(+0x146dd)[0x5590acb306dd]
[fv-az1695-570:12329] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f55c742a1ca]
[fv-az1695-570:12329] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f55c742a28b]
[fv-az1695-570:12329] [11] plumed_master(+0x15365)[0x5590acb31365]
[fv-az1695-570:12329] *** End of error message ***
</pre>
{% endraw %}
