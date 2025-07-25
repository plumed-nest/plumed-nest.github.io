**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  PLIT/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @34 : keyword ARG is compulsory for this action
[pkrvmpptgkbjq6m:06487] *** Process received signal ***
[pkrvmpptgkbjq6m:06487] Signal: Aborted (6)
[pkrvmpptgkbjq6m:06487] Signal code:  (-6)
[pkrvmpptgkbjq6m:06487] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa1eea45330]
[pkrvmpptgkbjq6m:06487] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa1eea9eb2c]
[pkrvmpptgkbjq6m:06487] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa1eea4527e]
[pkrvmpptgkbjq6m:06487] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa1eea288ff]
[pkrvmpptgkbjq6m:06487] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa1eeea5ff5]
[pkrvmpptgkbjq6m:06487] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa1eeebb0da]
[pkrvmpptgkbjq6m:06487] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa1eeea5a55]
[pkrvmpptgkbjq6m:06487] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa1eeea5a6f]
[pkrvmpptgkbjq6m:06487] [ 8] plumed_master(+0x146dd)[0x55da94a196dd]
[pkrvmpptgkbjq6m:06487] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa1eea2a1ca]
[pkrvmpptgkbjq6m:06487] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa1eea2a28b]
[pkrvmpptgkbjq6m:06487] [11] plumed_master(+0x15365)[0x55da94a1a365]
[pkrvmpptgkbjq6m:06487] *** End of error message ***
</pre>
{% endraw %}
