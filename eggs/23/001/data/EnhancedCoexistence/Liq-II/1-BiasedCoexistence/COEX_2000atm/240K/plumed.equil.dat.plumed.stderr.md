**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.equil.dat   
Download: [zipped raw stdout](plumed.equil.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.equil.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s9 : missing input file ice.pdb
[pkrvm7jw40e0xgp:07350] *** Process received signal ***
[pkrvm7jw40e0xgp:07350] Signal: Aborted (6)
[pkrvm7jw40e0xgp:07350] Signal code:  (-6)
[pkrvm7jw40e0xgp:07350] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f69d8845330]
[pkrvm7jw40e0xgp:07350] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f69d889eb2c]
[pkrvm7jw40e0xgp:07350] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f69d884527e]
[pkrvm7jw40e0xgp:07350] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f69d88288ff]
[pkrvm7jw40e0xgp:07350] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f69d8ca5ff5]
[pkrvm7jw40e0xgp:07350] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f69d8cbb0da]
[pkrvm7jw40e0xgp:07350] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f69d8ca5a55]
[pkrvm7jw40e0xgp:07350] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f69d8ca5a6f]
[pkrvm7jw40e0xgp:07350] [ 8] plumed(+0x146dd)[0x55f405c716dd]
[pkrvm7jw40e0xgp:07350] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f69d882a1ca]
[pkrvm7jw40e0xgp:07350] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f69d882a28b]
[pkrvm7jw40e0xgp:07350] [11] plumed(+0x15365)[0x55f405c72365]
[pkrvm7jw40e0xgp:07350] *** End of error message ***
</pre>
{% endraw %}
