**Project ID:** [plumID:23.016]({{ '/' | absolute_url }}eggs/23/016/)  
Stderr for source:  plumed_reweight_2D_microsw_adr_bin.dat   
Download: [zipped raw stdout](plumed_reweight_2D_microsw_adr_bin.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight_2D_microsw_adr_bin.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @87 : keyword ARG is compulsory for this action
[pkrvm7jw40e0xgp:06233] *** Process received signal ***
[pkrvm7jw40e0xgp:06233] Signal: Aborted (6)
[pkrvm7jw40e0xgp:06233] Signal code:  (-6)
[pkrvm7jw40e0xgp:06233] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb38ec45330]
[pkrvm7jw40e0xgp:06233] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb38ec9eb2c]
[pkrvm7jw40e0xgp:06233] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb38ec4527e]
[pkrvm7jw40e0xgp:06233] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb38ec288ff]
[pkrvm7jw40e0xgp:06233] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb38f0a5ff5]
[pkrvm7jw40e0xgp:06233] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb38f0bb0da]
[pkrvm7jw40e0xgp:06233] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb38f0a5a55]
[pkrvm7jw40e0xgp:06233] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb38f0a5a6f]
[pkrvm7jw40e0xgp:06233] [ 8] plumed_master(+0x146dd)[0x55ba95df46dd]
[pkrvm7jw40e0xgp:06233] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb38ec2a1ca]
[pkrvm7jw40e0xgp:06233] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb38ec2a28b]
[pkrvm7jw40e0xgp:06233] [11] plumed_master(+0x15365)[0x55ba95df5365]
[pkrvm7jw40e0xgp:06233] *** End of error message ***
</pre>
{% endraw %}
