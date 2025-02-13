**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  hbr/opes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @49 : keyword ARG is compulsory for this action
[fv-az1280-696:11872] *** Process received signal ***
[fv-az1280-696:11872] Signal: Aborted (6)
[fv-az1280-696:11872] Signal code:  (-6)
[fv-az1280-696:11872] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fcaebe45330]
[fv-az1280-696:11872] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fcaebe9eb2c]
[fv-az1280-696:11872] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fcaebe4527e]
[fv-az1280-696:11872] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fcaebe288ff]
[fv-az1280-696:11872] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fcaec2a5ff5]
[fv-az1280-696:11872] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fcaec2bb0da]
[fv-az1280-696:11872] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fcaec2a5a55]
[fv-az1280-696:11872] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fcaec2a5a6f]
[fv-az1280-696:11872] [ 8] plumed_master(+0x146dd)[0x564e4c7f16dd]
[fv-az1280-696:11872] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fcaebe2a1ca]
[fv-az1280-696:11872] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fcaebe2a28b]
[fv-az1280-696:11872] [11] plumed_master(+0x15365)[0x564e4c7f2365]
[fv-az1280-696:11872] *** End of error message ***
</pre>
{% endraw %}
