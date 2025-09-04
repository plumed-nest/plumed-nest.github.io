**Project ID:** [plumID:20.000]({{ '/' | absolute_url }}eggs/20/000/)  
Stderr for source:  reweighting/reweighting.dat   
Download: [zipped raw stdout](reweighting.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](reweighting.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @17 : keyword ARG is compulsory for this action
[pkrvm7jw40e0xgp:10849] *** Process received signal ***
[pkrvm7jw40e0xgp:10849] Signal: Aborted (6)
[pkrvm7jw40e0xgp:10849] Signal code:  (-6)
[pkrvm7jw40e0xgp:10849] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5b32445330]
[pkrvm7jw40e0xgp:10849] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5b3249eb2c]
[pkrvm7jw40e0xgp:10849] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5b3244527e]
[pkrvm7jw40e0xgp:10849] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5b324288ff]
[pkrvm7jw40e0xgp:10849] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5b328a5ff5]
[pkrvm7jw40e0xgp:10849] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5b328bb0da]
[pkrvm7jw40e0xgp:10849] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5b328a5a55]
[pkrvm7jw40e0xgp:10849] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5b328a5a6f]
[pkrvm7jw40e0xgp:10849] [ 8] plumed_master(+0x146dd)[0x559c3d5ac6dd]
[pkrvm7jw40e0xgp:10849] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5b3242a1ca]
[pkrvm7jw40e0xgp:10849] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5b3242a28b]
[pkrvm7jw40e0xgp:10849] [11] plumed_master(+0x15365)[0x559c3d5ad365]
[pkrvm7jw40e0xgp:10849] *** End of error message ***
</pre>
{% endraw %}
