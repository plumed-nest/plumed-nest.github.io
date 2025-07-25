**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-base/symm-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @44 : keyword ARG is compulsory for this action
[pkrvmpptgkbjq6m:08990] *** Process received signal ***
[pkrvmpptgkbjq6m:08990] Signal: Aborted (6)
[pkrvmpptgkbjq6m:08990] Signal code:  (-6)
[pkrvmpptgkbjq6m:08990] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f737ec45330]
[pkrvmpptgkbjq6m:08990] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f737ec9eb2c]
[pkrvmpptgkbjq6m:08990] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f737ec4527e]
[pkrvmpptgkbjq6m:08990] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f737ec288ff]
[pkrvmpptgkbjq6m:08990] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f737f0a5ff5]
[pkrvmpptgkbjq6m:08990] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f737f0bb0da]
[pkrvmpptgkbjq6m:08990] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f737f0a5a55]
[pkrvmpptgkbjq6m:08990] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f737f0a5a6f]
[pkrvmpptgkbjq6m:08990] [ 8] plumed_master(+0x146dd)[0x55b0c0b5b6dd]
[pkrvmpptgkbjq6m:08990] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f737ec2a1ca]
[pkrvmpptgkbjq6m:08990] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f737ec2a28b]
[pkrvmpptgkbjq6m:08990] [11] plumed_master(+0x15365)[0x55b0c0b5c365]
[pkrvmpptgkbjq6m:08990] *** End of error message ***
</pre>
{% endraw %}
