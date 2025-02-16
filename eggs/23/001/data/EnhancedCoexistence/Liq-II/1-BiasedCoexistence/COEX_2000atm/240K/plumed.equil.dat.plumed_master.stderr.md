**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.equil.dat   
Download: [zipped raw stdout](plumed.equil.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.equil.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s9 : missing input file ice.pdb
[fv-az1979-234:63512] *** Process received signal ***
[fv-az1979-234:63512] Signal: Aborted (6)
[fv-az1979-234:63512] Signal code:  (-6)
[fv-az1979-234:63512] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6c70445330]
[fv-az1979-234:63512] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6c7049eb2c]
[fv-az1979-234:63512] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6c7044527e]
[fv-az1979-234:63512] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6c704288ff]
[fv-az1979-234:63512] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6c708a5ff5]
[fv-az1979-234:63512] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6c708bb0da]
[fv-az1979-234:63512] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6c708a5a55]
[fv-az1979-234:63512] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6c708a5a6f]
[fv-az1979-234:63512] [ 8] plumed_master(+0x146dd)[0x561d395976dd]
[fv-az1979-234:63512] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6c7042a1ca]
[fv-az1979-234:63512] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6c7042a28b]
[fv-az1979-234:63512] [11] plumed_master(+0x15365)[0x561d39598365]
[fv-az1979-234:63512] *** End of error message ***
</pre>
{% endraw %}
