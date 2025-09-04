**Project ID:** [plumID:21.001]({{ '/' | absolute_url }}eggs/21/001/)  
Stderr for source:  HS6ST/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @47 : keyword ARG is compulsory for this action
[pkrvm7jw40e0xgp:12761] *** Process received signal ***
[pkrvm7jw40e0xgp:12761] Signal: Aborted (6)
[pkrvm7jw40e0xgp:12761] Signal code:  (-6)
[pkrvm7jw40e0xgp:12761] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ffb2aa45330]
[pkrvm7jw40e0xgp:12761] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ffb2aa9eb2c]
[pkrvm7jw40e0xgp:12761] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ffb2aa4527e]
[pkrvm7jw40e0xgp:12761] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ffb2aa288ff]
[pkrvm7jw40e0xgp:12761] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ffb2aea5ff5]
[pkrvm7jw40e0xgp:12761] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ffb2aebb0da]
[pkrvm7jw40e0xgp:12761] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ffb2aea5a55]
[pkrvm7jw40e0xgp:12761] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ffb2aea5a6f]
[pkrvm7jw40e0xgp:12761] [ 8] plumed_master(+0x146dd)[0x5587cff476dd]
[pkrvm7jw40e0xgp:12761] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ffb2aa2a1ca]
[pkrvm7jw40e0xgp:12761] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ffb2aa2a28b]
[pkrvm7jw40e0xgp:12761] [11] plumed_master(+0x15365)[0x5587cff48365]
[pkrvm7jw40e0xgp:12761] *** End of error message ***
</pre>
{% endraw %}
