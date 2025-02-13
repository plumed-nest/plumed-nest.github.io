**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  clch3cl/ch-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @36 : keyword ARG is compulsory for this action
[fv-az1280-696:13265] *** Process received signal ***
[fv-az1280-696:13265] Signal: Aborted (6)
[fv-az1280-696:13265] Signal code:  (-6)
[fv-az1280-696:13265] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f31c9a45330]
[fv-az1280-696:13265] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f31c9a9eb2c]
[fv-az1280-696:13265] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f31c9a4527e]
[fv-az1280-696:13265] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f31c9a288ff]
[fv-az1280-696:13265] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f31c9ea5ff5]
[fv-az1280-696:13265] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f31c9ebb0da]
[fv-az1280-696:13265] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f31c9ea5a55]
[fv-az1280-696:13265] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f31c9ea5a6f]
[fv-az1280-696:13265] [ 8] plumed_master(+0x146dd)[0x55b5c210f6dd]
[fv-az1280-696:13265] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f31c9a2a1ca]
[fv-az1280-696:13265] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f31c9a2a28b]
[fv-az1280-696:13265] [11] plumed_master(+0x15365)[0x55b5c2110365]
[fv-az1280-696:13265] *** End of error message ***
</pre>
{% endraw %}
