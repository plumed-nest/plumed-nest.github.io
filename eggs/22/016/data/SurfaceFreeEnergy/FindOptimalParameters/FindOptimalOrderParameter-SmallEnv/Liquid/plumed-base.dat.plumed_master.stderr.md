**Project ID:** [plumID:22.016]({{ '/' | absolute_url }}eggs/22/016/)  
Stderr for source:  SurfaceFreeEnergy/FindOptimalParameters/FindOptimalOrderParameter-SmallEnv/Liquid/plumed-base.dat   
Download: [zipped raw stdout](plumed-base.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-base.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @55 : keyword ARG is compulsory for this action
[pkrvm7jw40e0xgp:10659] *** Process received signal ***
[pkrvm7jw40e0xgp:10659] Signal: Aborted (6)
[pkrvm7jw40e0xgp:10659] Signal code:  (-6)
[pkrvm7jw40e0xgp:10659] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f526c645330]
[pkrvm7jw40e0xgp:10659] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f526c69eb2c]
[pkrvm7jw40e0xgp:10659] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f526c64527e]
[pkrvm7jw40e0xgp:10659] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f526c6288ff]
[pkrvm7jw40e0xgp:10659] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f526caa5ff5]
[pkrvm7jw40e0xgp:10659] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f526cabb0da]
[pkrvm7jw40e0xgp:10659] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f526caa5a55]
[pkrvm7jw40e0xgp:10659] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f526caa5a6f]
[pkrvm7jw40e0xgp:10659] [ 8] plumed_master(+0x146dd)[0x559b5a73c6dd]
[pkrvm7jw40e0xgp:10659] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f526c62a1ca]
[pkrvm7jw40e0xgp:10659] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f526c62a28b]
[pkrvm7jw40e0xgp:10659] [11] plumed_master(+0x15365)[0x559b5a73d365]
[pkrvm7jw40e0xgp:10659] *** End of error message ***
</pre>
{% endraw %}
