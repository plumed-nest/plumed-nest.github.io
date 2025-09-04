**Project ID:** [plumID:20.005]({{ '/' | absolute_url }}eggs/20/005/)  
Stderr for source:  input_data/classical/reweighting/reweighting.dat   
Download: [zipped raw stdout](reweighting.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](reweighting.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @16 : keyword ARG is compulsory for this action
[pkrvm7jw40e0xgp:10772] *** Process received signal ***
[pkrvm7jw40e0xgp:10772] Signal: Aborted (6)
[pkrvm7jw40e0xgp:10772] Signal code:  (-6)
[pkrvm7jw40e0xgp:10772] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa5f4845330]
[pkrvm7jw40e0xgp:10772] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa5f489eb2c]
[pkrvm7jw40e0xgp:10772] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa5f484527e]
[pkrvm7jw40e0xgp:10772] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa5f48288ff]
[pkrvm7jw40e0xgp:10772] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa5f4ca5ff5]
[pkrvm7jw40e0xgp:10772] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa5f4cbb0da]
[pkrvm7jw40e0xgp:10772] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa5f4ca5a55]
[pkrvm7jw40e0xgp:10772] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa5f4ca5a6f]
[pkrvm7jw40e0xgp:10772] [ 8] plumed_master(+0x146dd)[0x55577b8db6dd]
[pkrvm7jw40e0xgp:10772] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa5f482a1ca]
[pkrvm7jw40e0xgp:10772] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa5f482a28b]
[pkrvm7jw40e0xgp:10772] [11] plumed_master(+0x15365)[0x55577b8dc365]
[pkrvm7jw40e0xgp:10772] *** End of error message ***
</pre>
{% endraw %}
