**Project ID:** [plumID:20.026]({{ '/' | absolute_url }}eggs/20/026/)  
Stderr for source:  plumed_WTMD.dat   
Download: [zipped raw stdout](plumed_WTMD.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_WTMD.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @78 : keyword ARG is compulsory for this action
[pkrvm7jw40e0xgp:10268] *** Process received signal ***
[pkrvm7jw40e0xgp:10268] Signal: Aborted (6)
[pkrvm7jw40e0xgp:10268] Signal code:  (-6)
[pkrvm7jw40e0xgp:10268] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4ea3845330]
[pkrvm7jw40e0xgp:10268] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4ea389eb2c]
[pkrvm7jw40e0xgp:10268] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4ea384527e]
[pkrvm7jw40e0xgp:10268] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4ea38288ff]
[pkrvm7jw40e0xgp:10268] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4ea3ca5ff5]
[pkrvm7jw40e0xgp:10268] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4ea3cbb0da]
[pkrvm7jw40e0xgp:10268] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4ea3ca5a55]
[pkrvm7jw40e0xgp:10268] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4ea3ca5a6f]
[pkrvm7jw40e0xgp:10268] [ 8] plumed_master(+0x146dd)[0x5561330486dd]
[pkrvm7jw40e0xgp:10268] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4ea382a1ca]
[pkrvm7jw40e0xgp:10268] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4ea382a28b]
[pkrvm7jw40e0xgp:10268] [11] plumed_master(+0x15365)[0x556133049365]
[pkrvm7jw40e0xgp:10268] *** End of error message ***
</pre>
{% endraw %}
