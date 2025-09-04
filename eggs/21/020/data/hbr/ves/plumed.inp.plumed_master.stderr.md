**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  hbr/ves/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @51 : keyword ARG is compulsory for this action
[pkrvm7jw40e0xgp:10593] *** Process received signal ***
[pkrvm7jw40e0xgp:10593] Signal: Aborted (6)
[pkrvm7jw40e0xgp:10593] Signal code:  (-6)
[pkrvm7jw40e0xgp:10593] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1035845330]
[pkrvm7jw40e0xgp:10593] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f103589eb2c]
[pkrvm7jw40e0xgp:10593] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f103584527e]
[pkrvm7jw40e0xgp:10593] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f10358288ff]
[pkrvm7jw40e0xgp:10593] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1035ca5ff5]
[pkrvm7jw40e0xgp:10593] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1035cbb0da]
[pkrvm7jw40e0xgp:10593] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1035ca5a55]
[pkrvm7jw40e0xgp:10593] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1035ca5a6f]
[pkrvm7jw40e0xgp:10593] [ 8] plumed_master(+0x146dd)[0x556c485c36dd]
[pkrvm7jw40e0xgp:10593] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f103582a1ca]
[pkrvm7jw40e0xgp:10593] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f103582a28b]
[pkrvm7jw40e0xgp:10593] [11] plumed_master(+0x15365)[0x556c485c4365]
[pkrvm7jw40e0xgp:10593] *** End of error message ***
</pre>
{% endraw %}
