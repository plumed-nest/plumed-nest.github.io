**Project ID:** [plumID:23.005]({{ '/' | absolute_url }}eggs/23/005/)  
Stderr for source:  apo-5HT1A/plumed_reweight_microsw_5ht1a_rec.dat   
Download: [zipped raw stdout](plumed_reweight_microsw_5ht1a_rec.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight_microsw_5ht1a_rec.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @113 : keyword ARG is compulsory for this action
[pkrvm7jw40e0xgp:08115] *** Process received signal ***
[pkrvm7jw40e0xgp:08115] Signal: Aborted (6)
[pkrvm7jw40e0xgp:08115] Signal code:  (-6)
[pkrvm7jw40e0xgp:08115] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7faa70e45330]
[pkrvm7jw40e0xgp:08115] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7faa70e9eb2c]
[pkrvm7jw40e0xgp:08115] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7faa70e4527e]
[pkrvm7jw40e0xgp:08115] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7faa70e288ff]
[pkrvm7jw40e0xgp:08115] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7faa712a5ff5]
[pkrvm7jw40e0xgp:08115] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7faa712bb0da]
[pkrvm7jw40e0xgp:08115] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7faa712a5a55]
[pkrvm7jw40e0xgp:08115] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7faa712a5a6f]
[pkrvm7jw40e0xgp:08115] [ 8] plumed_master(+0x146dd)[0x5591294dc6dd]
[pkrvm7jw40e0xgp:08115] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7faa70e2a1ca]
[pkrvm7jw40e0xgp:08115] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7faa70e2a28b]
[pkrvm7jw40e0xgp:08115] [11] plumed_master(+0x15365)[0x5591294dd365]
[pkrvm7jw40e0xgp:08115] *** End of error message ***
</pre>
{% endraw %}
