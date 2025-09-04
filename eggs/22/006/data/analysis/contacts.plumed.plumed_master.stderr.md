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
[pkrvm7jw40e0xgp:08796] *** Process received signal ***
[pkrvm7jw40e0xgp:08796] Signal: Aborted (6)
[pkrvm7jw40e0xgp:08796] Signal code:  (-6)
[pkrvm7jw40e0xgp:08796] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff2f1845330]
[pkrvm7jw40e0xgp:08796] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff2f189eb2c]
[pkrvm7jw40e0xgp:08796] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff2f184527e]
[pkrvm7jw40e0xgp:08796] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff2f18288ff]
[pkrvm7jw40e0xgp:08796] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff2f1ca5ff5]
[pkrvm7jw40e0xgp:08796] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff2f1cbb0da]
[pkrvm7jw40e0xgp:08796] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff2f1ca5a55]
[pkrvm7jw40e0xgp:08796] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff2f1ca5a6f]
[pkrvm7jw40e0xgp:08796] [ 8] plumed_master(+0x146dd)[0x55a6268cd6dd]
[pkrvm7jw40e0xgp:08796] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff2f182a1ca]
[pkrvm7jw40e0xgp:08796] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff2f182a28b]
[pkrvm7jw40e0xgp:08796] [11] plumed_master(+0x15365)[0x55a6268ce365]
[pkrvm7jw40e0xgp:08796] *** End of error message ***
</pre>
{% endraw %}
