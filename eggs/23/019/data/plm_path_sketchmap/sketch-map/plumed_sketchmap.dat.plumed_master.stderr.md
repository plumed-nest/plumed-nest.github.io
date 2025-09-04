**Project ID:** [plumID:23.019]({{ '/' | absolute_url }}eggs/23/019/)  
Stderr for source:  plm_path_sketchmap/sketch-map/plumed_sketchmap.dat   
Download: [zipped raw stdout](plumed_sketchmap.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_sketchmap.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action VSTACK with label mat : keyword ARG is compulsory for this action
[pkrvm7jw40e0xgp:09741] *** Process received signal ***
[pkrvm7jw40e0xgp:09741] Signal: Aborted (6)
[pkrvm7jw40e0xgp:09741] Signal code:  (-6)
[pkrvm7jw40e0xgp:09741] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f30a2845330]
[pkrvm7jw40e0xgp:09741] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f30a289eb2c]
[pkrvm7jw40e0xgp:09741] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f30a284527e]
[pkrvm7jw40e0xgp:09741] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f30a28288ff]
[pkrvm7jw40e0xgp:09741] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f30a2ca5ff5]
[pkrvm7jw40e0xgp:09741] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f30a2cbb0da]
[pkrvm7jw40e0xgp:09741] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f30a2ca5a55]
[pkrvm7jw40e0xgp:09741] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f30a2ca5a6f]
[pkrvm7jw40e0xgp:09741] [ 8] plumed_master(+0x146dd)[0x5597b41896dd]
[pkrvm7jw40e0xgp:09741] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f30a282a1ca]
[pkrvm7jw40e0xgp:09741] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f30a282a28b]
[pkrvm7jw40e0xgp:09741] [11] plumed_master(+0x15365)[0x5597b418a365]
[pkrvm7jw40e0xgp:09741] *** End of error message ***
</pre>
{% endraw %}
