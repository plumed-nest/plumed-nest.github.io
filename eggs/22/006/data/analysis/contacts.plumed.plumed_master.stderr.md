**Project ID:** [plumID:22.006]({{ '/' | absolute_url }}eggs/22/006/)  
Stderr for source:  analysis/contacts.plumed   
Download: [zipped raw stdout](contacts.plumed.plumed_master.stdout.txt.zip) - [zipped raw stderr](contacts.plumed.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @92 : keyword ARG is compulsory for this action
[fv-az1046-619:07834] *** Process received signal ***
[fv-az1046-619:07834] Signal: Aborted (6)
[fv-az1046-619:07834] Signal code:  (-6)
[fv-az1046-619:07834] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3e26445330]
[fv-az1046-619:07834] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3e2649eb2c]
[fv-az1046-619:07834] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3e2644527e]
[fv-az1046-619:07834] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3e264288ff]
[fv-az1046-619:07834] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3e268a5ff5]
[fv-az1046-619:07834] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3e268bb0da]
[fv-az1046-619:07834] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3e268a5a55]
[fv-az1046-619:07834] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3e268a5a6f]
[fv-az1046-619:07834] [ 8] plumed_master(+0x146dd)[0x55a523a2d6dd]
[fv-az1046-619:07834] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3e2642a1ca]
[fv-az1046-619:07834] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3e2642a28b]
[fv-az1046-619:07834] [11] plumed_master(+0x15365)[0x55a523a2e365]
[fv-az1046-619:07834] *** End of error message ***
</pre>
{% endraw %}
