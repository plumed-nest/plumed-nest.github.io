**Project ID:** [plumID:22.006]({{ '/' | absolute_url }}eggs/22/006/)  
Stderr for source:  analysis/new_cvs.plumed   
Download: [zipped raw stdout](new_cvs.plumed.plumed_master.stdout.txt.zip) - [zipped raw stderr](new_cvs.plumed.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @94 : keyword ARG is compulsory for this action
[fv-az1374-136:64494] *** Process received signal ***
[fv-az1374-136:64494] Signal: Aborted (6)
[fv-az1374-136:64494] Signal code:  (-6)
[fv-az1374-136:64494] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb234a45330]
[fv-az1374-136:64494] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb234a9eb2c]
[fv-az1374-136:64494] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb234a4527e]
[fv-az1374-136:64494] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb234a288ff]
[fv-az1374-136:64494] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb234ea5ff5]
[fv-az1374-136:64494] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb234ebb0da]
[fv-az1374-136:64494] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb234ea5a55]
[fv-az1374-136:64494] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb234ea5a6f]
[fv-az1374-136:64494] [ 8] plumed_master(+0x146dd)[0x55872ad636dd]
[fv-az1374-136:64494] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb234a2a1ca]
[fv-az1374-136:64494] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb234a2a28b]
[fv-az1374-136:64494] [11] plumed_master(+0x15365)[0x55872ad64365]
[fv-az1374-136:64494] *** End of error message ***
</pre>
{% endraw %}
