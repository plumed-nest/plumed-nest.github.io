**Project ID:** [plumID:23.004]({{ '/' | absolute_url }}eggs/23/004/)  
Stderr for source:  BiasedCoexistence/IceIII/1-distributions/3000bar-295K/CalculateOptimalSigma/Liquid/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @87 : keyword ARG is compulsory for this action
[pkrvm7jw40e0xgp:07067] *** Process received signal ***
[pkrvm7jw40e0xgp:07067] Signal: Aborted (6)
[pkrvm7jw40e0xgp:07067] Signal code:  (-6)
[pkrvm7jw40e0xgp:07067] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0901445330]
[pkrvm7jw40e0xgp:07067] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f090149eb2c]
[pkrvm7jw40e0xgp:07067] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f090144527e]
[pkrvm7jw40e0xgp:07067] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f09014288ff]
[pkrvm7jw40e0xgp:07067] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f09018a5ff5]
[pkrvm7jw40e0xgp:07067] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f09018bb0da]
[pkrvm7jw40e0xgp:07067] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f09018a5a55]
[pkrvm7jw40e0xgp:07067] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f09018a5a6f]
[pkrvm7jw40e0xgp:07067] [ 8] plumed_master(+0x146dd)[0x56510ceb46dd]
[pkrvm7jw40e0xgp:07067] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f090142a1ca]
[pkrvm7jw40e0xgp:07067] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f090142a28b]
[pkrvm7jw40e0xgp:07067] [11] plumed_master(+0x15365)[0x56510ceb5365]
[pkrvm7jw40e0xgp:07067] *** End of error message ***
</pre>
{% endraw %}
