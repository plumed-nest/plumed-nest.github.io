**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  clch3cl/ccl-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @33 : keyword ARG is compulsory for this action
[fv-az1719-82:68848] *** Process received signal ***
[fv-az1719-82:68848] Signal: Aborted (6)
[fv-az1719-82:68848] Signal code:  (-6)
[fv-az1719-82:68848] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f627b245330]
[fv-az1719-82:68848] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f627b29eb2c]
[fv-az1719-82:68848] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f627b24527e]
[fv-az1719-82:68848] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f627b2288ff]
[fv-az1719-82:68848] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f627b6a5ff5]
[fv-az1719-82:68848] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f627b6bb0da]
[fv-az1719-82:68848] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f627b6a5a55]
[fv-az1719-82:68848] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f627b6a5a6f]
[fv-az1719-82:68848] [ 8] plumed_master(+0x146dd)[0x55b69efd06dd]
[fv-az1719-82:68848] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f627b22a1ca]
[fv-az1719-82:68848] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f627b22a28b]
[fv-az1719-82:68848] [11] plumed_master(+0x15365)[0x55b69efd1365]
[fv-az1719-82:68848] *** End of error message ***
</pre>
{% endraw %}
