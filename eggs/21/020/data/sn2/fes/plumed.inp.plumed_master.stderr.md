**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  sn2/fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @43 : keyword ARG is compulsory for this action
[pkrvm7jw40e0xgp:10399] *** Process received signal ***
[pkrvm7jw40e0xgp:10399] Signal: Aborted (6)
[pkrvm7jw40e0xgp:10399] Signal code:  (-6)
[pkrvm7jw40e0xgp:10399] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f687fc45330]
[pkrvm7jw40e0xgp:10399] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f687fc9eb2c]
[pkrvm7jw40e0xgp:10399] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f687fc4527e]
[pkrvm7jw40e0xgp:10399] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f687fc288ff]
[pkrvm7jw40e0xgp:10399] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f68800a5ff5]
[pkrvm7jw40e0xgp:10399] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f68800bb0da]
[pkrvm7jw40e0xgp:10399] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f68800a5a55]
[pkrvm7jw40e0xgp:10399] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f68800a5a6f]
[pkrvm7jw40e0xgp:10399] [ 8] plumed_master(+0x146dd)[0x55c3812086dd]
[pkrvm7jw40e0xgp:10399] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f687fc2a1ca]
[pkrvm7jw40e0xgp:10399] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f687fc2a28b]
[pkrvm7jw40e0xgp:10399] [11] plumed_master(+0x15365)[0x55c381209365]
[pkrvm7jw40e0xgp:10399] *** End of error message ***
</pre>
{% endraw %}
