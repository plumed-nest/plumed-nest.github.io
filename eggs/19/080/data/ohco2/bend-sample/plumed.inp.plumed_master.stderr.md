**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  ohco2/bend-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @33 : keyword ARG is compulsory for this action
[fv-az797-511:10482] *** Process received signal ***
[fv-az797-511:10482] Signal: Aborted (6)
[fv-az797-511:10482] Signal code:  (-6)
[fv-az797-511:10482] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8f20c45330]
[fv-az797-511:10482] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8f20c9eb2c]
[fv-az797-511:10482] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8f20c4527e]
[fv-az797-511:10482] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8f20c288ff]
[fv-az797-511:10482] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8f210a5ff5]
[fv-az797-511:10482] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8f210bb0da]
[fv-az797-511:10482] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8f210a5a55]
[fv-az797-511:10482] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8f210a5a6f]
[fv-az797-511:10482] [ 8] plumed_master(+0x146dd)[0x562c3a9af6dd]
[fv-az797-511:10482] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8f20c2a1ca]
[fv-az797-511:10482] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8f20c2a28b]
[fv-az797-511:10482] [11] plumed_master(+0x15365)[0x562c3a9b0365]
[fv-az797-511:10482] *** End of error message ***
</pre>
{% endraw %}
