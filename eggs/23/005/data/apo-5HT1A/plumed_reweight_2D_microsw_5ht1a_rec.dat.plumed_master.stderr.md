**Project ID:** [plumID:23.005]({{ '/' | absolute_url }}eggs/23/005/)  
Stderr for source:  apo-5HT1A/plumed_reweight_2D_microsw_5ht1a_rec.dat   
Download: [zipped raw stdout](plumed_reweight_2D_microsw_5ht1a_rec.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight_2D_microsw_5ht1a_rec.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @87 : keyword ARG is compulsory for this action
[pkrvm7jw40e0xgp:08076] *** Process received signal ***
[pkrvm7jw40e0xgp:08076] Signal: Aborted (6)
[pkrvm7jw40e0xgp:08076] Signal code:  (-6)
[pkrvm7jw40e0xgp:08076] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8ff1445330]
[pkrvm7jw40e0xgp:08076] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8ff149eb2c]
[pkrvm7jw40e0xgp:08076] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8ff144527e]
[pkrvm7jw40e0xgp:08076] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8ff14288ff]
[pkrvm7jw40e0xgp:08076] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8ff18a5ff5]
[pkrvm7jw40e0xgp:08076] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8ff18bb0da]
[pkrvm7jw40e0xgp:08076] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8ff18a5a55]
[pkrvm7jw40e0xgp:08076] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8ff18a5a6f]
[pkrvm7jw40e0xgp:08076] [ 8] plumed_master(+0x146dd)[0x55df868d96dd]
[pkrvm7jw40e0xgp:08076] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8ff142a1ca]
[pkrvm7jw40e0xgp:08076] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8ff142a28b]
[pkrvm7jw40e0xgp:08076] [11] plumed_master(+0x15365)[0x55df868da365]
[pkrvm7jw40e0xgp:08076] *** End of error message ***
</pre>
{% endraw %}
