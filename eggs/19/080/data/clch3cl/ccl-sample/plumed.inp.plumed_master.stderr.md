**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  clch3cl/ccl-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @32 : keyword ARG is compulsory for this action
[pkrvm7jw40e0xgp:11476] *** Process received signal ***
[pkrvm7jw40e0xgp:11476] Signal: Aborted (6)
[pkrvm7jw40e0xgp:11476] Signal code:  (-6)
[pkrvm7jw40e0xgp:11476] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6188245330]
[pkrvm7jw40e0xgp:11476] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f618829eb2c]
[pkrvm7jw40e0xgp:11476] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f618824527e]
[pkrvm7jw40e0xgp:11476] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f61882288ff]
[pkrvm7jw40e0xgp:11476] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f61886a5ff5]
[pkrvm7jw40e0xgp:11476] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f61886bb0da]
[pkrvm7jw40e0xgp:11476] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f61886a5a55]
[pkrvm7jw40e0xgp:11476] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f61886a5a6f]
[pkrvm7jw40e0xgp:11476] [ 8] plumed_master(+0x146dd)[0x55b46a2d26dd]
[pkrvm7jw40e0xgp:11476] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f618822a1ca]
[pkrvm7jw40e0xgp:11476] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f618822a28b]
[pkrvm7jw40e0xgp:11476] [11] plumed_master(+0x15365)[0x55b46a2d3365]
[pkrvm7jw40e0xgp:11476] *** End of error message ***
</pre>
{% endraw %}
