**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s10 : missing input file ice.pdb
[pkrvm7jw40e0xgp:07299] *** Process received signal ***
[pkrvm7jw40e0xgp:07299] Signal: Aborted (6)
[pkrvm7jw40e0xgp:07299] Signal code:  (-6)
[pkrvm7jw40e0xgp:07299] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f252d645330]
[pkrvm7jw40e0xgp:07299] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f252d69eb2c]
[pkrvm7jw40e0xgp:07299] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f252d64527e]
[pkrvm7jw40e0xgp:07299] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f252d6288ff]
[pkrvm7jw40e0xgp:07299] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f252daa5ff5]
[pkrvm7jw40e0xgp:07299] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f252dabb0da]
[pkrvm7jw40e0xgp:07299] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f252daa5a55]
[pkrvm7jw40e0xgp:07299] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f252daa5a6f]
[pkrvm7jw40e0xgp:07299] [ 8] plumed(+0x146dd)[0x56075622e6dd]
[pkrvm7jw40e0xgp:07299] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f252d62a1ca]
[pkrvm7jw40e0xgp:07299] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f252d62a28b]
[pkrvm7jw40e0xgp:07299] [11] plumed(+0x15365)[0x56075622f365]
[pkrvm7jw40e0xgp:07299] *** End of error message ***
</pre>
{% endraw %}
