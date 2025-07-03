**Project ID:** [plumID:22.006]({{ '/' | absolute_url }}eggs/22/006/)  
Stderr for source:  analysis/contacts.plumed   
Download: [zipped raw stdout](contacts.plumed.plumed_master.stdout.txt.zip) - [zipped raw stderr](contacts.plumed.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @88 : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:07684] *** Process received signal ***
[pkrvmbietmlfzoi:07684] Signal: Aborted (6)
[pkrvmbietmlfzoi:07684] Signal code:  (-6)
[pkrvmbietmlfzoi:07684] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3eb2245330]
[pkrvmbietmlfzoi:07684] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3eb229eb2c]
[pkrvmbietmlfzoi:07684] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3eb224527e]
[pkrvmbietmlfzoi:07684] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3eb22288ff]
[pkrvmbietmlfzoi:07684] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3eb26a5ff5]
[pkrvmbietmlfzoi:07684] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3eb26bb0da]
[pkrvmbietmlfzoi:07684] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3eb26a5a55]
[pkrvmbietmlfzoi:07684] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3eb26a5a6f]
[pkrvmbietmlfzoi:07684] [ 8] plumed_master(+0x146dd)[0x5568022f66dd]
[pkrvmbietmlfzoi:07684] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3eb222a1ca]
[pkrvmbietmlfzoi:07684] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3eb222a28b]
[pkrvmbietmlfzoi:07684] [11] plumed_master(+0x15365)[0x5568022f7365]
[pkrvmbietmlfzoi:07684] *** End of error message ***
</pre>
{% endraw %}
