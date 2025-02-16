**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s9 : missing input file ice.pdb
[fv-az1979-234:63602] *** Process received signal ***
[fv-az1979-234:63602] Signal: Aborted (6)
[fv-az1979-234:63602] Signal code:  (-6)
[fv-az1979-234:63602] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9a96445330]
[fv-az1979-234:63602] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9a9649eb2c]
[fv-az1979-234:63602] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9a9644527e]
[fv-az1979-234:63602] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9a964288ff]
[fv-az1979-234:63602] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9a968a5ff5]
[fv-az1979-234:63602] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9a968bb0da]
[fv-az1979-234:63602] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9a968a5a55]
[fv-az1979-234:63602] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9a968a5a6f]
[fv-az1979-234:63602] [ 8] plumed(+0x146dd)[0x55c8fa9056dd]
[fv-az1979-234:63602] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9a9642a1ca]
[fv-az1979-234:63602] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9a9642a28b]
[fv-az1979-234:63602] [11] plumed(+0x15365)[0x55c8fa906365]
[fv-az1979-234:63602] *** End of error message ***
</pre>
{% endraw %}
