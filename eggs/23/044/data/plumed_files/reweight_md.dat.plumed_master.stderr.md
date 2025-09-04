**Project ID:** [plumID:23.044]({{ '/' | absolute_url }}eggs/23/044/)  
Stderr for source:  plumed_files/reweight_md.dat   
Download: [zipped raw stdout](reweight_md.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](reweight_md.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @31 : keyword ARG is compulsory for this action
[pkrvm7jw40e0xgp:06325] *** Process received signal ***
[pkrvm7jw40e0xgp:06325] Signal: Aborted (6)
[pkrvm7jw40e0xgp:06325] Signal code:  (-6)
[pkrvm7jw40e0xgp:06325] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f45b6a45330]
[pkrvm7jw40e0xgp:06325] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f45b6a9eb2c]
[pkrvm7jw40e0xgp:06325] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f45b6a4527e]
[pkrvm7jw40e0xgp:06325] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f45b6a288ff]
[pkrvm7jw40e0xgp:06325] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f45b6ea5ff5]
[pkrvm7jw40e0xgp:06325] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f45b6ebb0da]
[pkrvm7jw40e0xgp:06325] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f45b6ea5a55]
[pkrvm7jw40e0xgp:06325] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f45b6ea5a6f]
[pkrvm7jw40e0xgp:06325] [ 8] plumed_master(+0x146dd)[0x562d158e46dd]
[pkrvm7jw40e0xgp:06325] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f45b6a2a1ca]
[pkrvm7jw40e0xgp:06325] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f45b6a2a28b]
[pkrvm7jw40e0xgp:06325] [11] plumed_master(+0x15365)[0x562d158e5365]
[pkrvm7jw40e0xgp:06325] *** End of error message ***
</pre>
{% endraw %}
