**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  5FU/iMetaD_Input/plumed_imetad.dat   
Download: [zipped raw stdout](plumed_imetad.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_imetad.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action PATH with label @s13 : keyword LAMBDA is compulsory for this action
[pkrvm7jw40e0xgp:08313] *** Process received signal ***
[pkrvm7jw40e0xgp:08313] Signal: Aborted (6)
[pkrvm7jw40e0xgp:08313] Signal code:  (-6)
[pkrvm7jw40e0xgp:08313] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f803b845330]
[pkrvm7jw40e0xgp:08313] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f803b89eb2c]
[pkrvm7jw40e0xgp:08313] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f803b84527e]
[pkrvm7jw40e0xgp:08313] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f803b8288ff]
[pkrvm7jw40e0xgp:08313] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f803bca5ff5]
[pkrvm7jw40e0xgp:08313] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f803bcbb0da]
[pkrvm7jw40e0xgp:08313] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f803bca5a55]
[pkrvm7jw40e0xgp:08313] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f803bca5a6f]
[pkrvm7jw40e0xgp:08313] [ 8] plumed_master(+0x146dd)[0x5573cfb316dd]
[pkrvm7jw40e0xgp:08313] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f803b82a1ca]
[pkrvm7jw40e0xgp:08313] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f803b82a28b]
[pkrvm7jw40e0xgp:08313] [11] plumed_master(+0x15365)[0x5573cfb32365]
[pkrvm7jw40e0xgp:08313] *** End of error message ***
</pre>
{% endraw %}
