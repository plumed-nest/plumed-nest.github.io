**Project ID:** [plumID:22.016]({{ '/' | absolute_url }}eggs/22/016/)  
Stderr for source:  SurfaceFreeEnergy/FindOptimalParameters/FindOptimalOrderParameter/IceIh/plumed-base.dat   
Download: [zipped raw stdout](plumed-base.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-base.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @55 : keyword ARG is compulsory for this action
[pkrvm7jw40e0xgp:10424] *** Process received signal ***
[pkrvm7jw40e0xgp:10424] Signal: Aborted (6)
[pkrvm7jw40e0xgp:10424] Signal code:  (-6)
[pkrvm7jw40e0xgp:10424] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe52f645330]
[pkrvm7jw40e0xgp:10424] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe52f69eb2c]
[pkrvm7jw40e0xgp:10424] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe52f64527e]
[pkrvm7jw40e0xgp:10424] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe52f6288ff]
[pkrvm7jw40e0xgp:10424] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe52faa5ff5]
[pkrvm7jw40e0xgp:10424] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe52fabb0da]
[pkrvm7jw40e0xgp:10424] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe52faa5a55]
[pkrvm7jw40e0xgp:10424] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe52faa5a6f]
[pkrvm7jw40e0xgp:10424] [ 8] plumed_master(+0x146dd)[0x5589a2aa66dd]
[pkrvm7jw40e0xgp:10424] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe52f62a1ca]
[pkrvm7jw40e0xgp:10424] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe52f62a28b]
[pkrvm7jw40e0xgp:10424] [11] plumed_master(+0x15365)[0x5589a2aa7365]
[pkrvm7jw40e0xgp:10424] *** End of error message ***
</pre>
{% endraw %}
