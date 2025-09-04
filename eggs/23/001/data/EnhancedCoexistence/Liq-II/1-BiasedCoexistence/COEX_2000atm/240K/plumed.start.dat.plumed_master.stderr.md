**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s9 : missing input file ice.pdb
[pkrvm7jw40e0xgp:07468] *** Process received signal ***
[pkrvm7jw40e0xgp:07468] Signal: Aborted (6)
[pkrvm7jw40e0xgp:07468] Signal code:  (-6)
[pkrvm7jw40e0xgp:07468] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6276045330]
[pkrvm7jw40e0xgp:07468] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f627609eb2c]
[pkrvm7jw40e0xgp:07468] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f627604527e]
[pkrvm7jw40e0xgp:07468] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f62760288ff]
[pkrvm7jw40e0xgp:07468] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f62764a5ff5]
[pkrvm7jw40e0xgp:07468] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f62764bb0da]
[pkrvm7jw40e0xgp:07468] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f62764a5a55]
[pkrvm7jw40e0xgp:07468] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f62764a5a6f]
[pkrvm7jw40e0xgp:07468] [ 8] plumed_master(+0x146dd)[0x55f961cca6dd]
[pkrvm7jw40e0xgp:07468] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f627602a1ca]
[pkrvm7jw40e0xgp:07468] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f627602a28b]
[pkrvm7jw40e0xgp:07468] [11] plumed_master(+0x15365)[0x55f961ccb365]
[pkrvm7jw40e0xgp:07468] *** End of error message ***
</pre>
{% endraw %}
