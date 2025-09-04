**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  DIDE-water/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @46 : keyword ARG is compulsory for this action
[pkrvm7jw40e0xgp:06778] *** Process received signal ***
[pkrvm7jw40e0xgp:06778] Signal: Aborted (6)
[pkrvm7jw40e0xgp:06778] Signal code:  (-6)
[pkrvm7jw40e0xgp:06778] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe807a45330]
[pkrvm7jw40e0xgp:06778] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe807a9eb2c]
[pkrvm7jw40e0xgp:06778] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe807a4527e]
[pkrvm7jw40e0xgp:06778] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe807a288ff]
[pkrvm7jw40e0xgp:06778] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe807ea5ff5]
[pkrvm7jw40e0xgp:06778] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe807ebb0da]
[pkrvm7jw40e0xgp:06778] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe807ea5a55]
[pkrvm7jw40e0xgp:06778] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe807ea5a6f]
[pkrvm7jw40e0xgp:06778] [ 8] plumed_master(+0x146dd)[0x55f7eb5c86dd]
[pkrvm7jw40e0xgp:06778] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe807a2a1ca]
[pkrvm7jw40e0xgp:06778] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe807a2a28b]
[pkrvm7jw40e0xgp:06778] [11] plumed_master(+0x15365)[0x55f7eb5c9365]
[pkrvm7jw40e0xgp:06778] *** End of error message ***
</pre>
{% endraw %}
