**Project ID:** [plumID:22.006]({{ '/' | absolute_url }}eggs/22/006/)  
Stderr for source:  analysis/new_cvs.plumed   
Download: [zipped raw stdout](new_cvs.plumed.plumed_master.stdout.txt.zip) - [zipped raw stderr](new_cvs.plumed.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @94 : keyword ARG is compulsory for this action
[fv-az1046-619:07897] *** Process received signal ***
[fv-az1046-619:07897] Signal: Aborted (6)
[fv-az1046-619:07897] Signal code:  (-6)
[fv-az1046-619:07897] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd10ea45330]
[fv-az1046-619:07897] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd10ea9eb2c]
[fv-az1046-619:07897] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd10ea4527e]
[fv-az1046-619:07897] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd10ea288ff]
[fv-az1046-619:07897] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd10eea5ff5]
[fv-az1046-619:07897] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd10eebb0da]
[fv-az1046-619:07897] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd10eea5a55]
[fv-az1046-619:07897] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd10eea5a6f]
[fv-az1046-619:07897] [ 8] plumed_master(+0x146dd)[0x55f79f1636dd]
[fv-az1046-619:07897] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd10ea2a1ca]
[fv-az1046-619:07897] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd10ea2a28b]
[fv-az1046-619:07897] [11] plumed_master(+0x15365)[0x55f79f164365]
[fv-az1046-619:07897] *** End of error message ***
</pre>
{% endraw %}
