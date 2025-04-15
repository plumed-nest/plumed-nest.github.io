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
[fv-az1719-82:69005] *** Process received signal ***
[fv-az1719-82:69005] Signal: Aborted (6)
[fv-az1719-82:69005] Signal code:  (-6)
[fv-az1719-82:69005] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f431e445330]
[fv-az1719-82:69005] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f431e49eb2c]
[fv-az1719-82:69005] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f431e44527e]
[fv-az1719-82:69005] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f431e4288ff]
[fv-az1719-82:69005] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f431e8a5ff5]
[fv-az1719-82:69005] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f431e8bb0da]
[fv-az1719-82:69005] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f431e8a5a55]
[fv-az1719-82:69005] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f431e8a5a6f]
[fv-az1719-82:69005] [ 8] plumed_master(+0x146dd)[0x55745999b6dd]
[fv-az1719-82:69005] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f431e42a1ca]
[fv-az1719-82:69005] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f431e42a28b]
[fv-az1719-82:69005] [11] plumed_master(+0x15365)[0x55745999c365]
[fv-az1719-82:69005] *** End of error message ***
</pre>
{% endraw %}
