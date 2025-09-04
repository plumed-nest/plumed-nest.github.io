**Project ID:** [plumID:19.050]({{ '/' | absolute_url }}eggs/19/050/)  
Stderr for source:  plumed_histogram.dat   
Download: [zipped raw stdout](plumed_histogram.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_histogram.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @32 : keyword ARG is compulsory for this action
[pkrvm7jw40e0xgp:13438] *** Process received signal ***
[pkrvm7jw40e0xgp:13438] Signal: Aborted (6)
[pkrvm7jw40e0xgp:13438] Signal code:  (-6)
[pkrvm7jw40e0xgp:13438] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9634845330]
[pkrvm7jw40e0xgp:13438] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f963489eb2c]
[pkrvm7jw40e0xgp:13438] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f963484527e]
[pkrvm7jw40e0xgp:13438] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f96348288ff]
[pkrvm7jw40e0xgp:13438] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9634ca5ff5]
[pkrvm7jw40e0xgp:13438] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9634cbb0da]
[pkrvm7jw40e0xgp:13438] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9634ca5a55]
[pkrvm7jw40e0xgp:13438] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9634ca5a6f]
[pkrvm7jw40e0xgp:13438] [ 8] plumed_master(+0x146dd)[0x5626282fc6dd]
[pkrvm7jw40e0xgp:13438] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f963482a1ca]
[pkrvm7jw40e0xgp:13438] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f963482a28b]
[pkrvm7jw40e0xgp:13438] [11] plumed_master(+0x15365)[0x5626282fd365]
[pkrvm7jw40e0xgp:13438] *** End of error message ***
</pre>
{% endraw %}
