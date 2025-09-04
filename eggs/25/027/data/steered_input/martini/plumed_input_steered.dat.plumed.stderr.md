**Project ID:** [plumID:25.027]({{ '/' | absolute_url }}eggs/25/027/)  
Stderr for source:  steered_input/martini/plumed_input_steered.dat   
Download: [zipped raw stdout](plumed_input_steered.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_input_steered.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label saxs : Residue not known: SOL
[pkrvm7jw40e0xgp:05657] *** Process received signal ***
[pkrvm7jw40e0xgp:05657] Signal: Aborted (6)
[pkrvm7jw40e0xgp:05657] Signal code:  (-6)
[pkrvm7jw40e0xgp:05657] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f614fe45330]
[pkrvm7jw40e0xgp:05657] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f614fe9eb2c]
[pkrvm7jw40e0xgp:05657] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f614fe4527e]
[pkrvm7jw40e0xgp:05657] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f614fe288ff]
[pkrvm7jw40e0xgp:05657] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f61502a5ff5]
[pkrvm7jw40e0xgp:05657] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f61502bb0da]
[pkrvm7jw40e0xgp:05657] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f61502a5a55]
[pkrvm7jw40e0xgp:05657] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f61502a5a6f]
[pkrvm7jw40e0xgp:05657] [ 8] plumed(+0x146dd)[0x55e304ca46dd]
[pkrvm7jw40e0xgp:05657] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f614fe2a1ca]
[pkrvm7jw40e0xgp:05657] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f614fe2a28b]
[pkrvm7jw40e0xgp:05657] [11] plumed(+0x15365)[0x55e304ca5365]
[pkrvm7jw40e0xgp:05657] *** End of error message ***
</pre>
{% endraw %}
