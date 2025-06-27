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
[pkrvmbietmlfzoi:63397] *** Process received signal ***
[pkrvmbietmlfzoi:63397] Signal: Aborted (6)
[pkrvmbietmlfzoi:63397] Signal code:  (-6)
[pkrvmbietmlfzoi:63397] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbe30a45330]
[pkrvmbietmlfzoi:63397] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbe30a9eb2c]
[pkrvmbietmlfzoi:63397] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbe30a4527e]
[pkrvmbietmlfzoi:63397] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbe30a288ff]
[pkrvmbietmlfzoi:63397] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbe30ea5ff5]
[pkrvmbietmlfzoi:63397] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbe30ebb0da]
[pkrvmbietmlfzoi:63397] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbe30ea5a55]
[pkrvmbietmlfzoi:63397] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbe30ea5a6f]
[pkrvmbietmlfzoi:63397] [ 8] plumed_master(+0x146dd)[0x5574210166dd]
[pkrvmbietmlfzoi:63397] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbe30a2a1ca]
[pkrvmbietmlfzoi:63397] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbe30a2a28b]
[pkrvmbietmlfzoi:63397] [11] plumed_master(+0x15365)[0x557421017365]
[pkrvmbietmlfzoi:63397] *** End of error message ***
</pre>
{% endraw %}
