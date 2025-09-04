**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.equil.dat   
Download: [zipped raw stdout](plumed.equil.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.equil.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s9 : missing input file ice.pdb
[pkrvm7jw40e0xgp:07365] *** Process received signal ***
[pkrvm7jw40e0xgp:07365] Signal: Aborted (6)
[pkrvm7jw40e0xgp:07365] Signal code:  (-6)
[pkrvm7jw40e0xgp:07365] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f29d7445330]
[pkrvm7jw40e0xgp:07365] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f29d749eb2c]
[pkrvm7jw40e0xgp:07365] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f29d744527e]
[pkrvm7jw40e0xgp:07365] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f29d74288ff]
[pkrvm7jw40e0xgp:07365] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f29d78a5ff5]
[pkrvm7jw40e0xgp:07365] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f29d78bb0da]
[pkrvm7jw40e0xgp:07365] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f29d78a5a55]
[pkrvm7jw40e0xgp:07365] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f29d78a5a6f]
[pkrvm7jw40e0xgp:07365] [ 8] plumed_master(+0x146dd)[0x5571bc5b66dd]
[pkrvm7jw40e0xgp:07365] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f29d742a1ca]
[pkrvm7jw40e0xgp:07365] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f29d742a28b]
[pkrvm7jw40e0xgp:07365] [11] plumed_master(+0x15365)[0x5571bc5b7365]
[pkrvm7jw40e0xgp:07365] *** End of error message ***
</pre>
{% endraw %}
