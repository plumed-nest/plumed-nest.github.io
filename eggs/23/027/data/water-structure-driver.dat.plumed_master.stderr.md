**Project ID:** [plumID:23.027]({{ '/' | absolute_url }}eggs/23/027/)  
Stderr for source:  water-structure-driver.dat   
Download: [zipped raw stdout](water-structure-driver.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](water-structure-driver.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @179 : keyword ARG is compulsory for this action
[pkrvm7jw40e0xgp:07434] *** Process received signal ***
[pkrvm7jw40e0xgp:07434] Signal: Aborted (6)
[pkrvm7jw40e0xgp:07434] Signal code:  (-6)
[pkrvm7jw40e0xgp:07434] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8e6ac45330]
[pkrvm7jw40e0xgp:07434] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8e6ac9eb2c]
[pkrvm7jw40e0xgp:07434] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8e6ac4527e]
[pkrvm7jw40e0xgp:07434] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8e6ac288ff]
[pkrvm7jw40e0xgp:07434] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8e6b0a5ff5]
[pkrvm7jw40e0xgp:07434] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8e6b0bb0da]
[pkrvm7jw40e0xgp:07434] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8e6b0a5a55]
[pkrvm7jw40e0xgp:07434] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8e6b0a5a6f]
[pkrvm7jw40e0xgp:07434] [ 8] plumed_master(+0x146dd)[0x563b395956dd]
[pkrvm7jw40e0xgp:07434] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8e6ac2a1ca]
[pkrvm7jw40e0xgp:07434] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8e6ac2a28b]
[pkrvm7jw40e0xgp:07434] [11] plumed_master(+0x15365)[0x563b39596365]
[pkrvm7jw40e0xgp:07434] *** End of error message ***
</pre>
{% endraw %}
