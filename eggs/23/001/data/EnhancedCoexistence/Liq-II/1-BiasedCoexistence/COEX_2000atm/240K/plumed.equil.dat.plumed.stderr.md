**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.equil.dat   
Download: [zipped raw stdout](plumed.equil.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.equil.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s9 : missing input file ice.pdb
[pkrvmpptgkbjq6m:08711] *** Process received signal ***
[pkrvmpptgkbjq6m:08711] Signal: Aborted (6)
[pkrvmpptgkbjq6m:08711] Signal code:  (-6)
[pkrvmpptgkbjq6m:08711] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f61eea45330]
[pkrvmpptgkbjq6m:08711] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f61eea9eb2c]
[pkrvmpptgkbjq6m:08711] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f61eea4527e]
[pkrvmpptgkbjq6m:08711] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f61eea288ff]
[pkrvmpptgkbjq6m:08711] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f61eeea5ff5]
[pkrvmpptgkbjq6m:08711] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f61eeebb0da]
[pkrvmpptgkbjq6m:08711] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f61eeea5a55]
[pkrvmpptgkbjq6m:08711] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f61eeea5a6f]
[pkrvmpptgkbjq6m:08711] [ 8] plumed(+0x146dd)[0x55e40bedd6dd]
[pkrvmpptgkbjq6m:08711] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f61eea2a1ca]
[pkrvmpptgkbjq6m:08711] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f61eea2a28b]
[pkrvmpptgkbjq6m:08711] [11] plumed(+0x15365)[0x55e40bede365]
[pkrvmpptgkbjq6m:08711] *** End of error message ***
</pre>
{% endraw %}
