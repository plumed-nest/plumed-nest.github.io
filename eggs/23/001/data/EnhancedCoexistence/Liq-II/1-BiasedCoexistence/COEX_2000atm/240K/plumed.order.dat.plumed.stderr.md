**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.order.dat   
Download: [zipped raw stdout](plumed.order.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.order.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s9 : missing input file ice.pdb
[pkrvm7jw40e0xgp:07401] *** Process received signal ***
[pkrvm7jw40e0xgp:07401] Signal: Aborted (6)
[pkrvm7jw40e0xgp:07401] Signal code:  (-6)
[pkrvm7jw40e0xgp:07401] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0ba4845330]
[pkrvm7jw40e0xgp:07401] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0ba489eb2c]
[pkrvm7jw40e0xgp:07401] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0ba484527e]
[pkrvm7jw40e0xgp:07401] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0ba48288ff]
[pkrvm7jw40e0xgp:07401] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0ba4ca5ff5]
[pkrvm7jw40e0xgp:07401] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0ba4cbb0da]
[pkrvm7jw40e0xgp:07401] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0ba4ca5a55]
[pkrvm7jw40e0xgp:07401] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0ba4ca5a6f]
[pkrvm7jw40e0xgp:07401] [ 8] plumed(+0x146dd)[0x55cbd35626dd]
[pkrvm7jw40e0xgp:07401] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0ba482a1ca]
[pkrvm7jw40e0xgp:07401] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0ba482a28b]
[pkrvm7jw40e0xgp:07401] [11] plumed(+0x15365)[0x55cbd3563365]
[pkrvm7jw40e0xgp:07401] *** End of error message ***
</pre>
{% endraw %}
