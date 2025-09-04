**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  Reweighting/plumed_reweight.dat   
Download: [zipped raw stdout](plumed_reweight.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_reweight.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label rho : could not find file named rtp_coord.dat
[pkrvm7jw40e0xgp:08397] *** Process received signal ***
[pkrvm7jw40e0xgp:08397] Signal: Aborted (6)
[pkrvm7jw40e0xgp:08397] Signal code:  (-6)
[pkrvm7jw40e0xgp:08397] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f068fc45330]
[pkrvm7jw40e0xgp:08397] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f068fc9eb2c]
[pkrvm7jw40e0xgp:08397] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f068fc4527e]
[pkrvm7jw40e0xgp:08397] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f068fc288ff]
[pkrvm7jw40e0xgp:08397] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f06900a5ff5]
[pkrvm7jw40e0xgp:08397] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f06900bb0da]
[pkrvm7jw40e0xgp:08397] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f06900a5a55]
[pkrvm7jw40e0xgp:08397] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f06900a5a6f]
[pkrvm7jw40e0xgp:08397] [ 8] plumed(+0x146dd)[0x560cf08646dd]
[pkrvm7jw40e0xgp:08397] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f068fc2a1ca]
[pkrvm7jw40e0xgp:08397] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f068fc2a28b]
[pkrvm7jw40e0xgp:08397] [11] plumed(+0x15365)[0x560cf0865365]
[pkrvm7jw40e0xgp:08397] *** End of error message ***
</pre>
{% endraw %}
