**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  PLIT-water/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @46 : keyword ARG is compulsory for this action
[pkrvm7jw40e0xgp:06957] *** Process received signal ***
[pkrvm7jw40e0xgp:06957] Signal: Aborted (6)
[pkrvm7jw40e0xgp:06957] Signal code:  (-6)
[pkrvm7jw40e0xgp:06957] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe39ca45330]
[pkrvm7jw40e0xgp:06957] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe39ca9eb2c]
[pkrvm7jw40e0xgp:06957] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe39ca4527e]
[pkrvm7jw40e0xgp:06957] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe39ca288ff]
[pkrvm7jw40e0xgp:06957] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe39cea5ff5]
[pkrvm7jw40e0xgp:06957] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe39cebb0da]
[pkrvm7jw40e0xgp:06957] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe39cea5a55]
[pkrvm7jw40e0xgp:06957] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe39cea5a6f]
[pkrvm7jw40e0xgp:06957] [ 8] plumed_master(+0x146dd)[0x559b15e896dd]
[pkrvm7jw40e0xgp:06957] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe39ca2a1ca]
[pkrvm7jw40e0xgp:06957] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe39ca2a28b]
[pkrvm7jw40e0xgp:06957] [11] plumed_master(+0x15365)[0x559b15e8a365]
[pkrvm7jw40e0xgp:06957] *** End of error message ***
</pre>
{% endraw %}
