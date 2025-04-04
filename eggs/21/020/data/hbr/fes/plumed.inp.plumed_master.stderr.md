**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  hbr/fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @52 : keyword ARG is compulsory for this action
[fv-az2207-973:09908] *** Process received signal ***
[fv-az2207-973:09908] Signal: Aborted (6)
[fv-az2207-973:09908] Signal code:  (-6)
[fv-az2207-973:09908] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd93b445330]
[fv-az2207-973:09908] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd93b49eb2c]
[fv-az2207-973:09908] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd93b44527e]
[fv-az2207-973:09908] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd93b4288ff]
[fv-az2207-973:09908] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd93b8a5ff5]
[fv-az2207-973:09908] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd93b8bb0da]
[fv-az2207-973:09908] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd93b8a5a55]
[fv-az2207-973:09908] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd93b8a5a6f]
[fv-az2207-973:09908] [ 8] plumed_master(+0x146dd)[0x5582373d66dd]
[fv-az2207-973:09908] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd93b42a1ca]
[fv-az2207-973:09908] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd93b42a28b]
[fv-az2207-973:09908] [11] plumed_master(+0x15365)[0x5582373d7365]
[fv-az2207-973:09908] *** End of error message ***
</pre>
{% endraw %}
